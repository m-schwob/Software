# Camera Considerations

## Camera Capabilities Characterization

### Last year conclusion (2019)

  Camera should preferably:
  - be ROS integrated
  - have built-in IMU 
  - be industrial: high dynamic range, global shutter, precise calibration
  - RGB is better than monochromatic although it depends on detector performance with grayscale images
  - have wide FOV
  - be stereo
  - have good SDK
  
  Question:
  - why do we need a build-in IMU?
  - what the meanning of 'high dynamic range'? pictures in different zoom?
  - what the meanning of 'global shutter'? what was the problem with the roll shutter?
  - what the meanning of 'precise calibration'? time stamp?
  - did they consider the Intel® RealSense™ Tracking Camera T265 camera?
  
 
### Additional requirements
  - ?
  

  
## Cameras Suggestion

### missing information

- **we need to characterize minimum and optional requirement first**

### links to information
- [ROS supported cameras](https://rosindustrial.org/3d-camera-survey/)


### Camera compartion
| Camera | ROS integrated | Sync | FOV | Frame Rate | Resolution | SDK | Interface |
| ------ | -------------- | ---- | --- | ---------- | ---------- | --- | ---------- |
| Intel® RealSense™ Tracking Camera T265 | yes | timestamp | 163±5° | 120 fps | ---------- | --- | USB 3.1 Gen 1 Micro B (USB2.0 supported) |
| Stereolabs® ZED™ | yes | ---- |  96° H, 54° V | 15 fps at max res., 120 fps at VGA res | 2208 x 1242 max | --- | USB 3.0 |
| Carnegie Robotics® MultiSense™ S7 | yes | 80° H, 45° V | --- | 15 fps at 2048 x 544 |  2048 x 1088 max | --- | Ethernet |
| Nerian SceneScan | yes | ---- | Variable |  100 fps | 1856 x 1856 max | --- | USB 3.0 to cameras, Gigabit Ethernet to Host |
| ------ | -------------- | ---- | --- | ---------- | ---------- | --- | ---------- |
| ------ | -------------- | ---- | --- | ---------- | ---------- | --- | ---------- |
| ------ | -------------- | ---- | --- | ---------- | ---------- | --- | ---------- |
| ------ | -------------- | ---- | --- | ---------- | ---------- | --- | ---------- |
