# Self-Navigating-Emergency-Rover-Using-Reinforcement-Algorithm

## **Overview**
This project is an autonomous robot that uses IR sensors for obstacle detection, motors for navigation, a servo motor for movement tasks, and a pump for specific actions. It dynamically adjusts to its environment, ensuring smooth operation.

## **Features**
1. **Obstacle Detection:** IR sensors detect obstacles on the front, left, and right.
2. **Motor Control:** Enables forward, backward, and turning movements.
3. **Servo Motor:** Sweeps between angles for scanning or interaction.
4. **Pump Activation:** Operates based on specific sensor triggers.
5. **Serial Debugging:** Displays sensor values for real-time feedback.

## **How It Works**
1. **Initialization:** Configures sensors, motors, and performs initial servo calibration.
2. **Navigation:** Moves or stops based on obstacle proximity detected by sensors.
3. **Actions:** Activates the pump and performs servo sweeps when conditions are met.
4. **Debugging:** Outputs sensor readings to the serial monitor.

## **Applications**
- Autonomous navigation in obstacle-prone areas.
- Use in agriculture, cleaning, or surveillance tasks.

## **Setup**
1. Assemble hardware: Connect sensors, motors, pump, and servo to the microcontroller.
2. Upload code via Arduino IDE and monitor serial outputs.
3. Test by placing obstacles and observing behavior.

---

This robot demonstrates basic autonomous functionality with potential for enhancements in navigation and task execution.
