# Temp-And-Humid

 Humidity and Temperature Sensor with Touch Screen LCD


In this file there is a draft and one i'm using temp_and_humid_2.ino the draft will have everything but you will have to change your TEMP AND HUMID default will be DHT22 i am using DHT11 also you will have to run the screen calibration test for your screen and enter it in the arduino code this is the default // run TouchScreen_Calibr_native.ino in MCUFRIEND_kbv examples to calibrate screen
// copy calibration data from serial monitor for XP, XM, YP, YM, TS_LEFT, TS_RT, TS_TOP, TS_BOT
const int XP = 7, XM = A1, YP = A2, YM = 6; //320x480 ID=0x0099
const int TS_LEFT = 903, TS_RT = 163, TS_TOP = 947, TS_BOT = 165;


and if you don't have the MCUFRIEND ex i will include it for you

Hope it helps and thanks for stopping by!!
