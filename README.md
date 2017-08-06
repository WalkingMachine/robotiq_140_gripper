# robotiq_140_gripper
Fork du package Robotiq_85_Gripper fournit par Stanley Innovation.
Le packet a été modifié pour être utilisé en harmonie avec le paquet [wm_robotiq_hardware_interface](https://github.com/WalkingMachine/wm_robotiq_hardware_interface).

### Instalation
```sh
cd <your workspace>/src
git clone git@github.com:WalkingMachine/sara_udev.git
git clone git@github.com:WalkingMachine/robotiq_140_description.git
git clone git@github.com:WalkingMachine/robotiq_140_gripper.git

cd <your workspace>
catkin_make
```
### Pour lancer
```sh
roslaunch robotiq_85_driver robotiq_85_driver.launch
```
