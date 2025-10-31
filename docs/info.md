<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

![https://www.electronics-tutorials.ws/wp-content/uploads/2018/05/sequential-seq26.gif]

## How to test

Power on the IC. All outputs should be toggling at 1/4 of the input clock frequency.

A more in-depth test is to connect all four output to a logic analyzer. Verify that you see the following pattern when power is applied:

Q_1 1-1-1-1-0-0-0-0
Q_2 0-1-1-1-1-0-0-0
Q_3 0-0-1-1-1-1-0-0
Q_4 0-0-0-1-1-1-1-0

## External hardware

None
