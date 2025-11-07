![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Air%20Pressure/%5B%20Multi%20%5D%20-%20%20Air%20Pressure%20Sensor.jpg?raw=true)

# Air-Pressure-Sensor
**The Air Pressure Sensor** is used to measure atmospheric pressure, which is essential for weather forecasting, altitude measurement, and environmental monitoring. The SPL06-001 is a high-precision, low-power digital barometric pressure and temperature sensor. Designed for compact applications, it supports both I²C and SPI interfaces, making it easy to integrate with various microcontrollers.
It accurately measures absolute pressure and includes a built-in temperature sensor for compensation, making it ideal for altitude tracking, weather monitoring, and indoor navigation systems.

## **This sensor is suitable for:**
- Motion detection system in Wearable Barometer
- Portable Weather Station
- Digital Altimeter

## **Specifications**
|Parameter|Value|
|-|-|
|**Model**|SPL06-001|
|**Measurable Pressure Range**|300 – 1,100 hPa|
|**Pressure Accuracy**|±1 hPa|
|**Supply Voltage**|1.7 - 3.6 VDC|
|**Temperature Range**|-40°C to 85°C|
|**Temperature Accuracy**|±0.5°C|
|**Max Current Consumption**|40 uA|
|**Dimension**|40 x 25 mm|
|**Wiring connection**|Black wire - GND (Ground)|
||Red wire - VCC (Power supply)|
||White wire - SDA (I²C data)|
||Yellow wire - SCL (I²C clock)| 

![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/Example%20code.png?raw=true){{{width="250" height="auto"}}} 
[**Download the working code here**](https://code.gogoboard.org/#/program/dfbc857c-857c-4bd2-8455-104239908a42)

## Block Code Reference
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Air%20Pressure/Pressure%20code%204.png?raw=true){{{width="150" height="auto"}}}| Use this block to read the pressure from the sensor in hectopascals (hPa).|
|-|-|
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Air%20Pressure/Pressure%20code%205.png?raw=true){{{width="170" height="auto"}}}|**Use this block to read the temperature from the sensor in degrees Celsius (°C).**|

## **Required Equipment**
|Air Pressure Sensor|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/sensor/air%20pressure%20front.png?raw=true){{{width="200" height="auto"}}}|
|-|-|
|**Grove cable**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/only%20grove%20(test).png?raw=true){{{width="200" height="auto"}}}|
|**Computer or Tablet**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/computer%20or%20tablet.png?raw=true){{{width="200" height="auto"}}}|
|**GoGo Board and USB-C cable**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/gogoboard%20and%20usb.png?raw=true){{{width="200" height="auto"}}}|

## **How to use**
**1. Connect the GoGo Board**
- Connect the GoGo Board to your computer or tablet via USB-C cable or Wi-Fi
![](https://github.com/thegogoboard/gogodoc/blob/main/Automation/Image%20(91).jpg?raw=true){{{width="500" height="auto"}}}

**2. Connect the Air Pressure Sensor**
- Connect the Air Pressure Sensor to a Grove cable, then plug the cable into the purple multi port on the GoGo Board.

|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Air%20Pressure/Pressure.gif?raw=true){{{width="500" height="auto"}}}|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Air%20Pressure/air%20pressure%20with%20board.png?raw=true){{{width="400" height="auto"}}}|
|-|-|

## Getting Started with the Air Pressure Sensor on GoGo Code 

**1. Visit the GoGo Code website:**
- Go to [GoGo Code](https://code.gogoboard.org/#/program) to start programming and controlling your device.

**2. Add the Air Pressure Sensor extension:**
- Click on the **Add Extension** category

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Air%20Pressure/Pressure%20code%201.gif?raw=true){{{width="1000" height="auto"}}}

- Select **Official**, then click the **[Multi] - Air Pressure Sensor** card. The system will automatically return to the main page.

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Air%20Pressure/Pressure%20code%202.gif?raw=true){{{width="1000" height="auto"}}}

**3. Add sensor command blocks:**
- Click on the **[Multi] - Air Pressure Sensor** category. You will see two available blocks:

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Air%20Pressure/Pressure%20code%203.gif?raw=true){{{width="1000" height="auto"}}}

**4. Write a simple program to display sensor data:**
- Use the “show number” block from the **Built-in Display** category to display the value on the GoGo Board screen.
- Insert the "**Pressure of SPL06 (hPa)"** block into the show number block
- To display the value continuously, place everything inside the **“forever do each time wait…”** block from the **Loops** category. You can also set how often the value should be updated (e.g., every 1 second).

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Air%20Pressure/Pressure%20code%206.png?raw=true){{{width="500" height="auto"}}} 

**5. Download and test your code:**
- Click **Download**, then click **Run Code** to start running your program.

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Air%20Pressure/Pressure%20code%207.gif?raw=true){{{width="1000" height="auto"}}}

::: details Additional information
 
**Buy online:** [Air Pressure Sensor](https://th.shp.ee/rwEkP5n)

**Cautions**
- Avoid modifying wires or connecting them incorrectly, as this may damage the device.
- Do not touch the sensor head while it is operating, as it may affect detection accuracy.
- If the sensor does not work, check the voltage and wiring connections.
:::
