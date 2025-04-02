# STM32F407VGT6 with IMU10DOF Sensor (Accelerometer & Gyroscope) via I2C

This project demonstrates how to interface an STM32F407VGT6 microcontroller with an IMU10DOF sensor (which includes an accelerometer and gyroscope) via the I2C communication protocol. The project reads the accelerometer and gyroscope values and prints them to a serial terminal for monitoring.

The IMU10DOF sensor combines multiple sensing modules, but in this project, we'll focus on extracting data from the Accelerometer and Gyroscope sensors.

# Features:

**I2C Communication:**

The IMU10DOF sensor communicates with the STM32F407VGT6 via the I2C interface.

The data from both the Accelerometer (X, Y, Z axes) and Gyroscope (X, Y, Z axes) are read and processed.

**Accelerometer and Gyroscope Data:**

Accelerometer: Provides the acceleration values along the X, Y, and Z axes in g (gravitational force).

Gyroscope: Provides the angular velocity values along the X, Y, and Z axes in °/s (degrees per second).

**Terminal Output:**

The raw data from the accelerometer and gyroscope is displayed in a serial terminal, allowing real-time monitoring of the sensor values.

# Pin Connections:

SCL → SCL (IMU10DOF)

SDA → SDA (IMU10DOF)

VCC → 3.3V or 5V Power Supply 

GND → Ground
