# 🏡 IoT Home Automation System

This project demonstrates a complete **IoT-based home automation system** that allows users to control home appliances remotely through a web interface. It is built using **Flask** for the backend, and devices are connected via **ESP8266** and controlled through **MQTT** protocol.

## 🚀 Features

- Control home appliances remotely via web or mobile.
- Real-time monitoring of appliance status.
- Integration with sensors (temperature, motion, etc.) for automated control.
- Customizable timer for scheduling appliance operations.
- Secure authentication for user access.
- Mobile-friendly user interface for ease of use.

## 🔧 Technologies Used

- **Flask** - Backend framework
- **ESP8266** - Microcontroller for IoT
- **MQTT** - Messaging protocol for communication between devices
- **HTML/CSS/JavaScript** - Frontend for web interface
- **Bootstrap** - Responsive design
- **Python** - Backend logic
- **MySQL** - Database to store user preferences and device status

## 📺 Project Demo

[![IoT Home Automation Video](https://img.youtube.com/vi/YourVideoID/0.jpg)](https://www.youtube.com/watch?v=YourVideoID)

Click above to watch a demo of the project in action.

## 💡 Devices Used

- **ESP8266 Wi-Fi Module**: For controlling the devices via the web.
- **Relays**: To switch household appliances on and off.
- **DHT11 Temperature Sensor**: For environmental monitoring.
- **Motion Sensor**: For automating lighting based on movement.
- **LEDs**: Used as indicator lights for appliance states.
- **Power Supply Unit**: To power the ESP8266 and connected components.

## ⚙️ Circuit Diagram

The complete circuit diagram for the setup is available [here](link-to-circuit-diagram).

---

## 📜 How to Use

1. Clone the repository.
2. Upload the code to your **ESP8266**.
3. Set up the required dependencies using `requirements.txt` in Flask.
4. Update the `config.py` with your **MQTT broker** and **Wi-Fi credentials**.
5. Run the Flask server and open the web interface to control your devices.

---

## 📫 Contributions

Feel free to fork this project and submit pull requests. Suggestions and feedback are always welcome!

---

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
