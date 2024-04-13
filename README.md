# rtabslam_ros2
Rtabmap mapping , localization and navigation


## launch for rtabmap (processing)
```ros2 launch rtabmap_launch rtabmap.launch.py     rtabmap_args:="--delete_db_on_start"     subscribe_rgbd:=true     rgbd_sync:=true     approx_synch:=false     rgb_topic:=/camera/image_raw     depth_topic:=/camera/depth/image_raw     camera_info_topic:=/camera/camera_info     frame_id:=camera_optical_link     approx_sync:=false     wait_imu_to_init:=false     qos:=1     rviz:=false```