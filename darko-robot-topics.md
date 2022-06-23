# 
In scenario 3, we record DARKO robot data from the following ros topics.

* Basic
```
/robot/robotnik_base_control/odom
/tf 
/tf_static
```
* Sensors
```
/robot/front_laser/scan
/robot/rear_laser/scan 
/robot/lidar_top_node/imu_packets 
/robot/lidar_top_node/lidar_packets
/robot/fisheye_rear/camera_info 
/robot/fisheye_rear/image_color/compressed 
/robot/fisheye_front/camera_info 
/robot/fisheye_front/image_color/compressed
/robot/k4a_top/rgb/camera_info 
/robot/k4a_top/rgb/image_raw/compressed 
/robot/k4a_top/depth/camera_info 
/robot/k4a_top/depth/image_raw/compressedDepth
/robot/k4a_top/rgb/rwth_metrabs/person_skeletons_associated_with_tracks
```
* Perception for people
```
/tracked_persons 
/tracked_persons_in_map_frame 
/tracked_persons_moving 
/tracked_persons_orientation_fixed 
```
