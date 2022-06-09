---
layout: post
title: what is Slot decorator used for in PySide6
---

网上查到以下信息：
1. `Slot`可以让不同的函数处理同一个信号的不同版本：https://stackoverflow.com/questions/14421897/is-the-pyside-slot-decorator-necessary
2. 官方的例子，大概也是解释了如何让不同的函数处理不同的信号版本：https://wiki.qt.io/Qt_for_Python_Signals_and_Slots
3. `Slot`的`name`参数可以指定名字，例如PySide6的官方文档：https://doc.qt.io/qtforpython/PySide6/QtCore/Slot.html?highlight=slot#PySide6.QtCore.PySide6.QtCore.Slot，