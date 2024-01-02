# MobileRobot-Openloopcontrol
## Aim:

To develop a python control code to move the mobilerobot along the predefined path.

## Equipments Required:
1. RoboMaster EP core
2. Python 3.7

## Procedure:

Step1:
Use from robomaster import robot

Step2:
Choose the x,y,z-axis movement distance(metres).

Step3:
Give ep_chassis.move to move straight

'Step4:
Give time.sleep() for a break.

'Step5:
Give ep_chassis.drive_speed to have a circular movement.

## Program
```python
from robomaster import robot
import time

if __name__ == '__main__':
    ep_robot = robot.Robot()
    ep_robot.initialize(conn_type="ap")

    ep_chassis = ep_robot.chassis
ep_robot robot. Robot()

ep_robot.initialize(conn_type="ap")

ep_chassis ep_robot.chassis

ep_led ep_robot.led

ep_camera ep_robot.camera

print("Video streaming started.....")

ep_camera.start_video_stream(display=True, resolution camera.STREAM_360P)

ep_chassis.move(x=2.5, y=0, z=0, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all", r=255,g=0, b=0, effect="on")

ep_chassis.move(x=0.4, y=0, z=80, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all", r=0,g=255, b=255, effect="on")

ep_chassis.move(x=1, y=0, z=0, xy speed-1.5).wait_for_completed() ep_led.set_led(comp = "all", r=255,g=204, b=0, effect="on")

ep_chassis.move(x=0, y=-1.5, z=0, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all", r=255,g=255, b=0, effect="on")

ep_chassis.move(x=0, y=0, z=60, xy_speed=1.5).wait_for_completed(). ep_led.set_led(comp = "all", r=255,g=0, b=255, effect="on")

ep_chassis.move(x=1.5, y=0, z=0, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all", r=204,g=255,b=255, effect="on")

ep_chassis.move(x=0, y=0, z=43, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all",r=255,g=128, b=128, effect="on")

ep_chassis.move(x=1.4, y=0, z=0, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp "all", r=255,g=128, b=128, effect="on")

ep_chassis.move(x=0, y=0, z=-85, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all", r=255,g=0, b=255, effect="on")

ep_chassis.move(x=-2, y=0, z=0, xy_speed=1.3).wait_for_completed() ep_led.set_led(comp = "all", r=0,g=255, b=255, effect="on")

ep_chassis.move(x=0, y=0, z=-98, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all",r=153,g=51, b=0, effect="on")

ep_chassis.move(x=0.6, y=0, z=0, xy_speed=1.3).wait_for_completed() ep_led.set_led(comp = "all", r=153,g=51, b=153, effect="on")

ep_chassis.move(x=0, y=0, z=0, xy_speed=1.3).wait_for_completed() ep_led.set_led(comp = "all",r=51,g=102,b=255, effect="on")



    
    ep_robot.close()

    
    
```

## MobileRobot Movement Image:

![image](https://github.com/23007232/mobilerobot-openloopcontrol/assets/139115574/777c8d25-c513-4578-9713-07ae2eb66bf1)

![image](https://github.com/23007232/mobilerobot-openloopcontrol/assets/139115574/ed01d9d4-ed73-41ab-bbc8-887c82f8e3fc)


## MobileRobot Movement Video:

![image](https://github.com/23007232/mobilerobot-openloopcontrol/assets/139115574/56a5368e-4d73-4f23-bb42-787c1a0ec6ae)

## Result:
Thus the python program code is developed to move the mobilerobot in the predefined path.

Mobile Robotics Laboratory
Department of Artificial Intelligence and Data Science/ Machine Learning
Saveetha Engineering College
```
