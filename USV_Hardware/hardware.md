# USV Hardware <img src="assets/img/neoylogo.jpg" alt="logo" width="20"/>
## _Concise and Correct_

Link for Flight controller
[![N|Solid](assets/img/link.jpg)](http://anotc.com/wiki/%E5%8C%BF%E5%90%8D%E4%BA%A7%E5%93%81%E8%B5%84%E6%96%99/%E6%8B%93%E7%A9%BA%E8%80%85p2/%E5%85%BC%E5%AE%B9%E7%89%88%E4%BB%8B%E7%BB%8D)



## Controller Specification:

- MCU: STM32F407
- PINS out:
  
![alt text](assets/img/a.png)

### 左图上5

- SWD：VCGD依次为：3.3V、CLK、GND、DIO
- UTI：凌霄IMU串口2
- IOB：拓展IO，具体见原理图
- IOA：拓展IO，具体见原理图
- RGB：GRBV依次为：绿、红、蓝、5V

### 左图下5

UT：串口，RTGV依次为：RX、TX、GND、5V

- UTI：无用
- UT1：GPS
- UT2：用户拓展
- UT3：用户拓展
- UT4：匿名光流
- UT5：数传

### 右图

- PWM：电调接口，数字代表第几通道
- CORE USB：核心板USB接口
- LX USB：凌霄IMU的USB接口
- SBUS：GVS依次为：GND、5V、Signal
- BAT：电池接口，+接电池正极，-接电池负极


