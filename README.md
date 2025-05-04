# 🏡 IoT Home Automation System

This project demonstrates a complete **IoT-based home automation system** that allows users to control home appliances remotely through a web interface. It is built using **Arduino Programming** and devices are connected via **ESP32**

## 🚀 Features

- Control home appliances remotely via web or mobile.
- Real-time monitoring of appliance status.
- Integration with sensors (temperature, motion, etc.) for automated control.
- Customizable timer for scheduling appliance operations.
- Secure authentication for user access.
- Mobile-friendly user interface for ease of use.

## 🔧 Circuit Diagram

![PHOTO-2024-09-27-18-24-10](https://github.com/user-attachments/assets/943f61eb-26b3-4fa0-b4b7-c9d05dbf7f88)

## 📺 Project Demo

https://github.com/user-attachments/assets/119c21f8-8e55-4dc6-bba1-810574e399d4



Click above to watch a demo of the project in action.

## 💡 Devices Used

- **ESP32**: For controlling the devices via the web.
  ![61o2ZUzB4XL](https://github.com/user-attachments/assets/b826cad4-fd46-4673-81b3-80502810c45b)
- **5V 4-Channel Relay**: To switch household appliances on and off.
  ![71PQ9K7dRLL _AC_UF1000,1000_QL80_](https://github.com/user-attachments/assets/42d51b88-3c9d-4efb-8de5-0d5f97705a70)
- **5V 2-Channel Relay**: For environmental monitoring.
  ![image](https://github.com/user-attachments/assets/e0d5c693-5ca2-455b-b622-04dd2d195547)
- **Hi-Link 220V AC to 5V DC Converter**: For automating lighting based on movement.
  ![hlk-5m05-hi-link-5v-5w-ac-to-dc-power-supply-module](https://github.com/user-attachments/assets/a1e7fe40-a330-478b-a770-82a001178255)
- **Jumper Wires**: In this project we use all types of Jumper Wires. 1. Male-to-Male 2. Male-to-Female 3. Female-to-Female
  ![image](https://github.com/user-attachments/assets/d75dc2be-7ded-4b61-bca9-715441b92490)
- **PCB Board**: We also used a PCB Board to mount all the Components on it.
  ![51ow5wlcU3L _AC_](https://github.com/user-attachments/assets/60e8c683-7e4f-4fea-b2c6-a31b77c8b51a)
- **Soldering Machine and Wire**: To mount all components on **PCB Board** we use **Soldering Machine** and **Soldering Wire**.
  ![image](https://github.com/user-attachments/assets/f32574ed-f751-419b-a85b-0125a9e88fcb)
- **2 Pin and 3 Pin PCB Mount**: To connect wires we use **2 Pin and 3 Pin PCB Mounts**.
  ![image](https://github.com/user-attachments/assets/4de8535b-3eb2-4229-84db-d863275bc2ed)
- **Digital Multimemter**: To test all the electircal current we use a **Digital Multimeter**.
  ![image](https://github.com/user-attachments/assets/4b10049b-1160-41cc-b78b-ad30ba118649)

All the devices are not necessary, to implement the same as the above demo video i recommend to use all the devices with Precaution and considering all the safety measures.

## 📜 How to Use

1. Clone the repository.
2. Upload the code to your **ESP32** using **Arduino IDE**.
3. Click on **Tools** and set the **Partition Scheme** to **RainMaker**.
4. Set the **Upload Speed** and **Baud Rate** to **11520**
5. Compile the code by clicking on the **Verify** button on the Top Left Corner.

I encountered some problems while compiling my code, so if you encounter same problems than I am providing you some articles to solve those problems.
1. https://github.com/SensorsIot/Bluetooth-BLE-on-Arduino-IDE/issues/3
2. https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads 
3. https://medium.com/@adihendro/esp32-built-in-led-blinking-4dd0b50264a

## ⚙️ How to Setup

1. After successful compile **Upload** the code by clicking on the button next to **Verify**.
2. After successful uploading the code you might not see any output in the console, to view output click on **Serial Monitor**.
3. Go to **Tools** and click on **Serial Monitor**.
4. You will see a **QR Code** and a link to the QR Code.
5. Download the **ESP RainMaker** Mobile Application and Scan the **QR Code**. Further Proceses are mentioned in the ****ESP RainMaker Mobile Applicaion****.

[![Watch the video](https://i.ytimg.com/vi/7knQaSuEgsU/mqdefault.jpg)]([https://youtu.be/T-D1KVIuvjA](https://youtu.be/7knQaSuEgsU?si=ftGWDExrnD4hquuj))

I am also uploading a YouTube video for reference.

---

## 📫 Contributions

@Abhishek Sreesukan :- Wiring and Circuit Connection. :)

Feel free to fork this project and submit pull requests. Suggestions and feedback are always welcome!

---

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
