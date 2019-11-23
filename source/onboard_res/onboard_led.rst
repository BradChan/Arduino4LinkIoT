.. _onboard_led:

===============================
可编程LED (BUILTIN_LED)
===============================

可以用很多文本编辑工具编写python代码，比如系统自带的记事本、`Notepad`_ 等。我们建议使用Mu。Mu支持CircuitPython，并集成了串口控制台，使用简单方便。

.. _Notepad: https://notepad-plus-plus.org

BlinkLED
+++++++++
打开Mu工具，点击左上角“新建”按钮创建一个文件。

.. image:: ../_static/intro/editor/code_new.png

拷贝并黏贴以下代码到Mu代码编辑窗口

.. code-block:: python
   :linenos:

   import board
   import digitalio
   import time

   led = digitalio.DigitalInOut(board.D13)
   led.direction = digitalio.Direction.OUTPUT

   while True:
      led.value = True
      time.sleep(0.5)
      led.value = False
      time.sleep(0.5)



.. note:: 需要注意while True以下的四行需要缩进对齐
.. image:: ../_static/intro/editor/code_new1.png

点击“保存”按钮，以文件名“code.py”保存到CIRCUITPY磁盘。