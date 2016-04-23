# MSX_PC_PS3BT_XBOXRECV
# by cloudree@naver.com

PC Game Controller for MSX (with Arduino USB Host)

HW :
Arduino Uno
Arduino USB Host Shield 
MSX Joystick Cable

Pin Out:
MSX        Arduino
1 Up ----- D2
2 Down --- D3
3 Left --- D4
4 Right -- D5
5 5V ----- 5V
6 TR1 ---- D6
7 TR2 ---- D7
8 Out
9 GND ---- GND

PS 3 Controller + BlueTooth Support : 
#define SUPPORT_PS3
//#define SUPPORT_XBOX
//#define SUPPORT_PC

XBox 360 Controller + Wireless Receiver Support : 
//#define SUPPORT_PS3
#define SUPPORT_XBOX
//#define SUPPORT_PC