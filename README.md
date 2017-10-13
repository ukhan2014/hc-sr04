# hc-sr04
ultrasonic distance sensor


Python code runs in raspi. Dumps distance ~ every 0.1s.

Echo pin is 5V so must be lowered to 3.3V before input to raspi. Needs voltage divider.

Vcc -> 5V out on raspi
Trig -> pin 16 on raspi
Echo -> divider -> pin 18 on raspi