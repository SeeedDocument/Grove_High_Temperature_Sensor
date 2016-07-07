# Grove - High Temperature Sensor
----------
## Introduction ##
【**[中文版本](http://www.seeedstudio.com/wiki/Grove_-_High_Temperature_Sensor_%E4%BC%A0%E6%84%9F%E5%99%A8)**】

![Grove - High Temperature Sensor](https://statics3.seeedstudio.com/product/High%20Temperature%20Sensor_01.jpg)

Thermocouples are very sensitive, requiring a good amplifier with a cold - compensation reference. The Grove - Temperature Sensor USES a K type thermocouple Temperature detection, with a Thermistor to detect The ambient Temperature as Temperature compensation. The detectable range of this Sensor is -50-600℃ , and The accuracy is ±(2.0% + 2℃)

[![enter image description here](http://www.seeedstudio.com/wiki/images/thumb/d/d0/Get_One_Now_Banner.png/150px-Get_One_Now_Banner.png)](http://www.seeedstudio.com/depot/Breakout-for-LinkIt-Smart-7688-v20-p-2641.html)

## Specifications ##
|---|---|
|:---|:---:|
|**Voltage**|3.3V ~ 5V|
|**Max power rating at 25℃** |300mW|
|**Operating temperature range**|-40℃ ~ +125 ℃|
|**Range of temperature measurement** | -50℃ ~ +600 ℃|
|**Amplifier output voltage range** | 0 ~ 3.3 mV |
|**Thermocouple temperature measurement accuracy** | ± (2.0% + 2 ℃)|
|**Cold junction compensation** (environment temperature measurement) |


## Getting Started ##
Here is an example to show you how to read temperature information from the sensor.
We need a Seeeduino V3.0 and a Grove - High Temperature Sensor.

### Hardware Installation ###
There's a I2C Port on Seeeduino, actually it's connect to A4 and A5 else. So we can use this port to read data from the sensor.
Let's plug this sensor to I2C port of Seeeduino.

### Download Code and Upload ###
You can download the library in **[here](https://github.com/Seeed-Studio/Grove_HighTemp_Sensor/archive/master.zip)**
Then extract the library the Library folder of Arduino, open the demo in examples folder.
Then upload it to your Seeeduino.

### Open Serial Monitor and Get Data ###
Then, open your Serial Monitor, you can find the temperature in Celsius here.
![](http://www.seeedstudio.com/wiki/images/1/13/Htsdata.jpg)

### K type thermocouple indexing table ###
As a reference, the following is K type thermocouple indexing table. 
![](http://www.seeedstudio.com/wiki/images/7/74/Ktype.jpg)

### Resource ###
- **[Grove High Temperature Sensor PDF](http://www.seeedstudio.com/wiki/images/1/17/Grove_-_High_Temperature_Sensor_v1.0.pdf)**
- **[Grove High Temperature Sensor Eagle File](http://www.seeedstudio.com/wiki/images/2/24/Grove_-_High_Temperature_Sensor_v1.0_20140225.zip)**
- **[High Temperature Sensor Library](https://github.com/Seeed-Studio/Grove_HighTemp_Sensor)**
- **[Datasheet OPA333 PDF](http://www.ti.com/lit/ds/symlink/opa333.pdf)**
- **[Datasheet LMV358 PDF](http://www.seeedstudio.com/wiki/images/6/6e/Lmv358.pdf)**

##Is this page helpful?
<iframe style="height: 600px; width: 500px; margin: 10px 0 10px;" allowTransparency="true" src="https://www.surveymonkey.com/r/LJWFSQN" frameborder="0"></iframe>