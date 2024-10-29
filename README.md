# vue.js Web Development for Robotics 

- To get rosbridge_address

```
rosbridge_address
```

- To get webpage_address

```
webpage_address
```

- Call Http Server

```
python -m SimpleHTTPServer 7000
```

- Rosbridge Server

```
roslaunch course_web_dev_ros web.launch
```


## Unit 06

Terminal 1

```
rosrun web_video_server web_video_server _port:=11315
```

Terminal 2

```
roslaunch course_web_dev_ros web.launch
```

Terminal 3

```
cd ~/webpage_ws/unit_06
python -m SimpleHTTPServer 7000
```

Terminal 4

```
rosbridge_address
webvideo_address
webpage_address
```

## Unit 07 

Terminal 1

```
cd ~/webpage_ws/unit_07
python -m SimpleHTTPServer 7000
```

Terminal 2

```
roslaunch course_web_dev_ros web.launch
```

Terminal 3

```
rosrun course_web_dev_ros hector_services_copy.py
```

Terminal 4

```
rosbridge_address
webpage_address
```


## Unit 08

Terminal 1

```
cd ~/webpage_ws/unit_08
python -m SimpleHTTPServer 7000
```

Terminal 2

```
roslaunch course_web_dev_ros web.launch
```

Terminal 3

```
roslaunch course_web_dev_ros mapping.launch
```

Terminal 4

```
rosbridge_address
webpage_address
```

## Unit 09

Terminal 1

```
cd ~/webpage_ws/unit_09
python -m SimpleHTTPServer 7000
```

Terminal 2

```
roslaunch course_web_dev_ros web.launch
```

Terminal 3

```
rosrun course_web_dev_ros robot_params.py
```

Terminal 4

```
rosbridge_address
webpage_address
```


## Unit_10

Terminal 1

```
cd ~/webpage_ws/unit_10
python -m SimpleHTTPServer 7000
```

Terminal 2

```
roslaunch course_web_dev_ros web.launch
```

Terminal 3

```
roslaunch course_web_dev_ros tf2_web.launch
```

Terminal 4

```
cp -R $(rospack find pmb2_description) ~/webpage_ws/unit_10/
cp -R $(rospack find tiago_description) ~/webpage_ws/unit_10/
rosbridge_address
webpage_address
```

## Unit_11

Terminal 1

```
cd ~/webpage_ws/unit_11
python -m SimpleHTTPServer 7000
```

Terminal 2

```
roslaunch course_web_dev_ros web.launch
```

Terminal 3

```
rosrun course_web_dev_ros turtlebot_2_action_server.py
```

Terminal 4

```
rosbridge_address
webpage_address
```

pub to action Server

```
rostopic pub /turtlebot2_action_service_as/goal course_web_dev_ros/WaypointActionActionGoal "header:
  seq: 0
  stamp:
    secs: 0
    nsecs: 0
  frame_id: ''
goal_id:
  stamp:
    secs: 0
    nsecs: 0
  id: ''
goal:
  position:
    x: 3.0
    y: 3.0
    z: 0.0"
```