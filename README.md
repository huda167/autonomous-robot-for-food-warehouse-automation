# autonomous-robot-for-food-warehouse-automation


In this work, we aim to develop an intelligent robot that automates the process of transporting food items within a warehouse, completely eliminating the need for human intervention. This improves efficiency, saves time, and reduces human error.

Workflow (Execution Algorithm):

The robot starts by initializing its systems and checking that all components (sensors, camera, robotic arm) are functioning properly.
It connects to the central system to receive a task.
Using its sensors, it identifies its current location and the location of the target item.
The robot navigates to the specified location while avoiding obstacles.
It verifies the target box using barcode or tag scanning.
The robotic arm picks up the box.
The robot moves to the assigned destination (e.g., another shelf or storage zone).
It carefully places the box in the designated spot.
A confirmation is sent to the system, and the robot either waits for a new task or goes to recharge if needed.

Robot Design:

The robot consists of several key components designed for optimal performance in a warehouse environment:

Wheeled Mobile Base: 
Allows smooth movement around the warehouse.
Multi-axis Robotic Arm: Used for picking and placing boxes.
Smart Camera: For object recognition and barcode/tag reading.
Multiple Sensors (e.g., LIDAR): For obstacle avoidance and indoor positioning.
Weight Sensor: Measures the load and confirms item pickup.
Rechargeable Battery: Enables fully wireless operation.
Central Control Unit: Executes commands and coordinates all systems.
Working Envelope:
The robot's arm must cover the full range of targeted shelves.
Arm movement angle: 180°–360° depending on the design.
Varying vertical reach to handle boxes of different heights.
Safety clearance around the robot to prevent collisions.
Dedicated charging zone when the battery runs low.
