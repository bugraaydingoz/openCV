# openCV

Clone into your racecar-controller folder under your workspace:
```sh
cd ~/racecar_ws/src/racecar-controller/
git clone https://github.com/bugraaydingoz/openCV.git
```

In one terminal run roscore:
```sh
roscore
```

In second terminal run teleop package:
```sh
source devel/setup.bash
roslaunch racecar teleop.launch
```

In third terminal run opencv code:
```sh
source devel/setup.bash
rosrun openCV opencv.py
```
