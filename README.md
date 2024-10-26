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