This repository contains ROS packages for working with
raw GPS data, sufficient to create a GPS/INS system
useful on an outdoor robot.

Sensors required:

1. An IMU (inertial measurement unit) and driver publishing
   `sensor_msgs/Imu` and `sensor_msgs/MagneticField` messages
2. A GPS receiver providing raw observables supported by one of the
   drivers in this repository:
    1. Skytraq S1315F-RAW
    2. NVS NV08C-CSM

This software was sponsored as NSF project #00108192.
