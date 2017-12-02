# README #

#IR Sensor Calibration
https://github.com/DrGFreeman/SharpDistSensor
https://github.com/daPhoosa/MedianFilter

Note 1: To calibrate, measure the analogue voltage values coming from the sensors yourself, put onto excel,
bring up scatter plot graph, and get polynomial best fit line equation and plug into code.

#Hall Affect Encoder
### How to use interrupts: ###
http://gammon.com.au/interrupts
https://www.arduino.cc/reference/en/language/functions/external-interrupts/attachinterrupt/
https://arduino.stackexchange.com/questions/1784/how-many-interrupt-pins-can-an-uno-handle

### How to use the encoders + motors ###
http://andrewjkramer.net/motor-encoders-arduino/
Note: There are only two interrupt pins on the Arudino Uno: D2 and D3
#Motor Control
### How to use a DC Motor 101 ###
https://www.youtube.com/watch?v=dyjo_ggEtVU&t=1669s
# Hareware Used #
Magnetic encoder sensors:
https://www.pololu.com/product/3081/resources

Micro Metal gearmotor
https://www.pololu.com/product/2216

White wheels:
https://www.pololu.com/product/1454

Bracket:
https://www.pololu.com/product/989

Caster Wheels:
https://www.pololu.com/product/951

### Useful PID Info ###
Using Adjust += Wall Following:
https://www.arduino.cc/reference/en/language/structure/compound-operators/compoundaddition/
This uses Wall following method to inspect one wall and try to balance sensor to certain set value.



