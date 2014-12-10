raspberry-twoline-display
=========================


<h1>About</h1>

Small C Programm to interface between user / shell and a 1602 LCD Display
on a raspberry pi.

Prerequisite to compiling is gcc, make, wiringpi

<h1>Status</h1>

When currently comiled it can be used to pipe any text into it which will
then be shown on the display, however no sanitization check is done and any
length is currently allowed.
