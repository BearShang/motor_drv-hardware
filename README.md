# 变更记录

- 取消反向二极管和栅极驱动电阻。
- 电源多了一路 LDO，直接产生 12V 电压。
- 减少了 GNDP 端大电容，只保留 104 电容。
- 取消了单片机到驱动的电阻，布局再紧凑一点。

# 原理图预览

## PWR
![alt text](pics/image.png)
## MCU
![alt text](pics/image-1.png)
## Driver
![alt text](pics/image-2.png)
## Sensing
![alt text](pics/image-3.png)