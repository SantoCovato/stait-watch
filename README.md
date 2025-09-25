# Stait Watch ⌚

Stait Watch is a personal smartwatch project developed from scratch as part of my passion for **embedded systems, software development, and IoT**.  
It combines **hardware design**, **firmware programming**, and **interactive user interface** to create a fully functional wearable device.
The goal of Stait Watch is to explore the integration of **hardware and software**, to learn embedded programming, and to create a device that is both functional and customizable.  
This project is part of my personal brand *Stait*, which represents my initiative to develop innovative technology solutions.

## 🛠️ Hardware

The hardware of Stait Watch is built around an ESP32-S3 microcontroller, chosen for its performance and support for Wi-Fi and Bluetooth Low Energy (BLE). The device features a 1.28-inch round touch LCD from Waveshare, providing an interactive user interface directly on the watch. It is powered by a 400 mAh Li-Po battery, with a design focused on low power consumption and efficient energy management. I designed and 3D-printed the watch casing, creating a compact and durable enclosure that houses all the components neatly. The smartwatch is designed to be modular and extensible, allowing future integration of sensors such as vibration motor, heart rate monitors and wireless charging. The hardware layout emphasizes compactness, reliability, and usability, while supporting seamless connectivity with the mobile app through BLE for real-time data exchange and control from a smartphone.

## 💻 Software & Firmware

The software of Stait Watch is designed to provide a smooth and responsive user experience. The smartwatch firmware is developed in C using Arduino IDE, while the user interface is created with SquareLine Studio. Currently, the watch includes a Home screen, displaying the time, date, and current weather, a Settings screen, where the brightness adjustment is functional, a Music screen, and a Notifications screen, which are currently designed in the UI but not yet fully implemented. The software architecture is modular and extensible, allowing for future development of additional features and sensors.

Complementing the smartwatch, I developed a mobile app called Stait Watch Link using Flutter, which connects to the ESP32-S3 via Bluetooth Low Energy (BLE). The app retrieves the smartphone’s location to fetch accurate weather information through the Open-Meteo API. Currently, the app includes a single button to search and connect to the watch. Once connected, the ESP32 receives the current time, date, and weather data from the app. This integration of embedded firmware and mobile application ensures real-time synchronization and interaction between the smartwatch and smartphone, laying the foundation for future features such as music control and notifications.

## 🎯 Future Roadmap

- Fully implement the Settings screen, including all planned functionalities.

- Develop the Notifications screen to receive and display alerts from the smartphone.

- Complete the Music screen with full control over playback.

- Implement a step counter using the ESP32-S3 integrated accelerometer.

- Update weather data every 30 minutes for accurate real-time information.

- Create an extended Weather screen to display the 7-day forecast.

- Optimize battery consumption to achieve at least one full day of autonomy.
