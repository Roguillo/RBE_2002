Final code for Mock Garbage Collection Robot for Unified Robotics II: Sensing (RBE 2002)

- Throughout this course, I worked alongside 3 other team members to develop an autonomous differential drive robot capable of filtering and utilizing data from various sensors to complete a "garbage" collection routine
- An IMU was used to keep track of orientation and identify when driving onto or off of ramps by referring to the fused data of gyroscope and accelerometer to avoid spikes in readings
- A camera, along with a lightweight object detection model, was used to identify and align with apriltags, which assisted the robot in locating the "trash cans"
- In order to lift these cans, the robot was fitted with a 3D-printed arm powered by a servo at its base, and a load cell at its end for weighing "garbage". Data from the load cell was amplified by an instrumentation amplifier, then passed into a transfer function to determine weight
- Additionally, odometry was implemented in order to keep track of position and orientation for ease of motion. An ultrasonic sensor was also used for avoiding obstacles

Videos
- [Romi Train](https://youtube.com/shorts/aRKS1n_RtuU?feature=share)
- [MQTT](https://youtube.com/shorts/aRKS1n_RtuU?feature=share) 