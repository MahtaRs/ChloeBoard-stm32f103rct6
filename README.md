You Can easily use the product using the basic STM32CubeMx config I have put in Chloe Basics directory.

You can use STlink to program the board.

The basic is also LED BLINK project.

In order to use the micro sd you can enable SDIO in 1bit mode the widen the bus to use it in 4 bit. ( If you initialize it in 4 bit right away it would not start due to a bug from STM32CubeMx and from ST company's side itself.

In order to use the USB you can easily enable it in FS mode in STM32CubeMx.

The on board button is connected to PC4 and it has no external pull up or pull down but it as a parallel 100nF capacitor next to it. you can use it as GPIO_INPUT or External interrupt but an Internal Pull Up MUST BE ADDED.

The green on board LED in connected to PC13.
