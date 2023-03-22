# TangNano-9K-example

- [TangNano-9K-example](#tangnano-9k-example)
  - [Question](#question)
    - [Error Code RP2017](#error-code-rp2017)
  - [Examples](#examples)
    - [led](#led)
    - [lcd\_led](#lcd_led)
    - [lcd\_4.3](#lcd_43)
    - [picotiny](#picotiny)
    - [hdmi](#hdmi)
    - [spi\_lcd](#spi_lcd)

## Question

### Error Code RP2017

When you meet error code `PR2017`. Do what is shown below.(Just enable corresponding IO as regular IO)

![PR2017](.assets/ERROR%20CODE%20PR2017.png "PR2017")

## Examples

### led

Demo project for drive LED and on board led.
LED guide is at <https://wiki.sipeed.com/hardware/en/tang/Tang-Nano-Doc/examples.html>

<img src="./.assets/blink.gif" alt="led">

### lcd_led

Demo project for drive RGB LCD and on board led, to drive the 5 inch RGB screen with 800*480 resolution.

![lcd](./.assets/lcd_led.jpg)

### lcd_4.3

Demo project for drive RGB LCD and on board led, to drive the 4.3 inch RGB screen with 480*272 resolution.

![3_colorbar](./.assets/lcd_4.3_colorbar.jpg)

### picotiny

A PicoRV32-based SoC example with HDMI terminal from SimpleVout, SPI Flash XIP from picosoc, and custom UART ISP for flash programming. UART baudrate default at `115200`.

See [README.md](picotiny/README.md) for detailed description. 

- Visit https://wiki.sipeed.com/hardware/en/tang/Tang-Nano-9K/examples/picorv/picorv.html to quick run this example
- 中文访问 https://wiki.sipeed.com/hardware/zh/tang/Tang-Nano-9K/examples/picorv/picorv.html 来快速使用

![picorv](./.assets/picorv.jpg)

### hdmi

Project based on picotiny example, but all soft_core related codes are removed.

### spi_lcd

This is an example to drive the 1.14 inch lcd screen which can connect with this board.

Be sure match board with screen in the same order

![spi_lcd](./.assets/spi_lcd.jpg)