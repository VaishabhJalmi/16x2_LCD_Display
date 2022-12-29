# 16x2_LCD_Display
Code to interface with Arduino and 16x2 lcd  display

Features of LCD16x2
The features of this LCD mainly include the following.

The operating voltage of this LCD is 4.7V-5.3V
It includes two rows where each row can produce 16-characters.
The utilization of current is 1mA with no backlight
Every character can be built with a 5×8 pixel box
The alphanumeric LCDs alphabets & numbers
Is display can work on two modes like 4-bit & 8-bit

![lcd-16x2-pin-diagram](https://user-images.githubusercontent.com/69182306/209987556-c59cabe4-37b5-4dbd-8530-39fddbd7119e.jpg)


Registers of LCD
A 16×2 LCD has two registers like data register and command register. The RS (register select) is mainly used to change from one register to another. When the register set is ‘0’, then it is known as command register. Similarly, when the register set is ‘1’, then it is known as data register.
