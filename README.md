# [C-C-C-C-Combo Breaker](http://samy.pl/combobreaker/)

This is an updated version of the original [C-C-C-C-ComboBreaker project by SamyK](https://github.com/samyk/combobreaker)

PCB has been completely redesigned from scratch with an improved and updated power circuit, I2C display support, and silk screen labels for all connections.

![image](https://user-images.githubusercontent.com/25337485/31258678-e4bf40ce-aa0e-11e7-9c1e-e49d0bd33a3a.png)

![image](https://user-images.githubusercontent.com/25337485/31258684-ed7eeec6-aa0e-11e7-97bb-8510a92d3c90.png)



**[Combo Breaker](http://samy.pl/combobreaker/)** is a motorized, battery powered, 3D printed, Arduino-based combination lock cracking device. It is portable, open source, 3D models provided, and exploits a new technique I've discovered for [cracking combination locks in 8 attempts or less](https://www.youtube.com/watch?v=09UgmwtL12c), but in an even more exciting, automated fashion.

-----

# (U) Hardware

[![Combo Breaker](http://samy.pl/combobreaker/sIMG_2916.JPG)](http://samy.pl/combobreaker/sIMG_2916.JPG)

### [Arduino Nano](http://amzn.to/1QLlf23)
**$12**: A [5V Arduino Nano](http://amzn.to/1QLlf23) microcontroller is used as the brains of the project.

### [Allegro A4988](http://amzn.to/1L3q7fK)
**$7**: Instead of the EasyDriver, I upgraded to a smaller, yet more powerful stepper driver that can go up to 1 amp (1000mA).

### [Double Shaft Stepper Motor](http://www.phidgets.com/products.php?product_id=3320)
**$16**: This double shaft stepper motor allows you to build the more advanced Combo Breaker while employing an optical rotary encoder on the back to detect the position of the stepper when the dial stops turning (which is part of the exploit employed).

### [HKT22 Optical Rotary Encoder](http://www.phidgets.com/products.php?product_id=3531)
**$25**: For use **only** with the double shaft stepper motor, this optical rotary encoder lets us know what position the shaft of the stepper motor is at and allows us to employ an exploit on Master combination locks where the stepper will get locked into certain grooves within the internal combination disc of the lock.

### [Analog Feedback Servo](https://www.adafruit.com/products/1404)
**$15**: This servo not only provides the torque we need to lift the shackle (90.26 oz*in), but has an additional wire providing analog feedback that we use to detect the state of the shackle and whether it has opened or not.

### [OKI-78SR Voltage Regulator](http://amzn.to/1A28XOt)
**$6**: This is far more efficient and reliable than the original L7805

-----

# (U) Software

### Combo Breaker
Combo Breaker's source code can be obtained in entirety from my github: <https://github.com/samyk/combobreaker>

[![Combo Breaker 3D Print](http://samy.pl/combobreaker/model.jpg)](http://samy.pl/combobreaker/model.jpg)

-----

# (U) 3D Models

I've included the 3D models on my github: <https://github.com/samyk/combobreaker>
 
[![Combo Breaker 3D Print](http://samy.pl/combobreaker/smodel.png)](http://samy.pl/combobreaker/smodel.png)

[![Combo Breaker](http://samy.pl/combobreaker/sIMG_2919.JPG)](http://samy.pl/combobreaker/sIMG_2919.JPG)

-----