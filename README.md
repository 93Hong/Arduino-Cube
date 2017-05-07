# Arduino-Cube

## Motivation
- Most of the famous restaurants are crowded with many employees and customers.
- We tried using Arduino to create a vibrating bell and add a few features to solve this problem.

## Description
- We added a gyro sensor, vibration sensor, acoustic sensor, and Bluetooth sensor to Arduino.
- Using these sensors, I created a cube that performs ordering and ringtone functions.
- We also built the database on the server and recorded the order information.

## Language
- C (Arduino), Node.js (Server)

## Function
- On the six sides of the cube, We put the food menu and the employee call function.
- When you place the cube on the table with the desired menu facing up, the vibration is detected and the order enters.
- It communicates with the server via a Bluetooth sensor
- Stores the information in the database by separating the table and the date.
![](./img/1.jpg)

## Kalman Filter
- We used the Kalman filter algorithm to reduce the error between the vibration sensor and the gyro sensor to get accurate orders.
![](./img/2.jpg)
