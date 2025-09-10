# Step-Counter-Pedometer-
A simple wearable step counter project using an accelerometer sensor and OLED display, with power switch and reset functionality. Built with Arduino for health and fitness monitoring applications.

# Step Counter with OLED Display  

## Short Description  
This project is a **step counter** that uses an **accelerometer sensor** to detect and count steps, while displaying real-time data on an **OLED screen**. It’s designed as a simple wearable prototype that helps monitor movement without needing a smartphone app.  

## Features  
- Counts steps using accelerometer readings   
- Displays live step count on the OLED screen   
- Power ON/OFF control with switch   
- Reset button to clear step count   
- Low-cost, beginner-friendly wearable prototype   

## Components Used  
**Hardware**  
- ESP32 / Arduino board  
- Accelerometer sensor (e.g., MPU6050 / ADXL345)  
- OLED Display (SSD1306 or similar)  
- Push button (Reset)  
- Power switch  
- Breadboard + jumper wires  

**Software**  
- Arduino IDE  
- Wire.h & Adafruit Sensor libraries (or equivalent for your accelerometer)  
- Adafruit SSD1306 / U8g2 library for OLED  

##  How It Works  
1. The accelerometer continuously measures movement in **x, y, z axes (g-forces)**.  
2. The code calculates the **acceleration magnitude** from these axes.  
3. When the magnitude crosses a **threshold value (e.g., > 1.39 g)**, it’s detected as a step.  
4. Each valid step increases the step counter.  
5. The **OLED screen** updates in real-time to show the step count.  
6. The **reset button** clears the step count, and the **power switch** turns the device ON/OFF.  

## 👤 Author  
**Master QAT** – *Student | AI & Robotics Enthusiast | Future Robotics Engineer 🚀*  
