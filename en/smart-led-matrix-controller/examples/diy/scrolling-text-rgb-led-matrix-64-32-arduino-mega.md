---
date: "2019-10-11"
author:
  display_name: "UseMyTools"
draft: "false"
toc: true
title: "Scrolling Text On RGB Led Matrix 64x32 Using Arduino Mega"
linktitle: "Scrolling Text On RGB Led Matrix 64x32 Using Arduino Mega"
menu:
  docs:
    identifier: "smc-scrolling-text-rgb-led-matrix-64-32-arduino-mega"
    parent: "smc-diy"
    weight: "01"
lastmod: "2021-01-20"
weight: "01"
---

## Scrolling Text Using RGB Led Matrix 64x32 With Arduino Mega ##

This DIY example I will guide you howto scroll text messages on RGB Led Matrix Panel using Arduino Mega board.

## Hardware Used ##

I have used P5 Indoor LED Panel Digital Screen Module 320x160mm 64x32 Dots Pixel RGB Full Color LED Advertising Board for this example.

This matrix has 2048 bright RGB LEDs arranged in a 64x32 grid on the front. On the back, there are two IDC connectors (one input, one output: in theory you can chain these together) and 12 16-bit latches that allow you to drive the display with a 1:16 scan rate.


`Note` We can't use an Arduino UNO to drive this size as it is too big for it. We can use Arduino Mega, Raspberry Pi and other boards that can handle displaying to RGB matrices and has plenty of RAM.

## Hardware Setup ##

Please use following connection between LED Matrix Panel 64x32 with Arduino Mega board.

![](../rgb-led-matrix-64-32-arduino-mega-connection.png)

## Source Code ##

{{< gist usemytools 2d3bd36a9231262433a3d7d8000f833d "scrolling-text-message-rgb-matrix-64-32-arduino-mega.ino">}}


## Compile and Upload Arduino Mega Board ##

You can also download source code from our [Github repo](https://github.com/usemytools/smart-automation-tools.git). Please compile and upload to Arduino Mega Board. It will seamlessly run on you LED Panel Digital Screen of 64x32.


## Scrolling Text Using RGB Led Matrix 64x32 With Arduino Mega Video Guide ##
{{< youtube nqGJuCUM_U0 >}}
