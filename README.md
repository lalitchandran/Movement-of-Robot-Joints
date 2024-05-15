# EX 8: Movement-of-Robot-Joints
## Aim:  
To move and drive the joints of the robot using python API.

## Equipment’s required:

Visual Components Premium 4.3

## Procedure:

1. 	In the eCatalog panel, Collections view, browse to Models by Type>Robots>Visual Components and then add a Generic Articulated Robot to the 3D world.
2. 	Click the Modeling tab, and then add a Python Script behaviour. The script editor will open automatically when you add the behaviour.
3. 	In the script editor, add the code and then compile the code.

## Program
```python
Developed by: S LALIT CHANDRAN
RegisterNumber: 212223240077
from vcScript import *
from vcHelpers.Robot2 import *
def OnRun():
  pos=[[1,30],[2,40],[3,90]]
  robot = getRobot()
  robot.driveJoints(0,0,0,0,0,0)
  delay(5)
  for i in pos:
    robot.Controller.moveJoint(i[0],i[1])
    delay(5)
```
## Output
### 1. Generic Articulated Robot
![vc 1](https://github.com/Divya110205/Movement-of-Robot-Joints/assets/119404855/280c64f8-a3eb-46bf-a48e-ad7b595e42ed)
### 2. robot.driveJoints(0,0,0,0,0,0)
![vc 2](https://github.com/Divya110205/Movement-of-Robot-Joints/assets/119404855/ace04059-707a-40a5-8234-545b1cfd31ba)
### 3. Movement of Joint1
![vc 3](https://github.com/Divya110205/Movement-of-Robot-Joints/assets/119404855/b3c06a4b-3dd2-40f5-a7e2-544dbd1d0ad7)
### 4. Movement of Joint2
![vc 4](https://github.com/Divya110205/Movement-of-Robot-Joints/assets/119404855/ad5f8f7d-f838-4860-9c62-8a93f4602fb3)
### 5. Movement of Joint3
![vc 5](https://github.com/Divya110205/Movement-of-Robot-Joints/assets/119404855/4e3b0b85-df67-470c-932b-0962c386dd62)
## Result 
Thus the different robots joints are moved with the help of python list.


    
 


  



