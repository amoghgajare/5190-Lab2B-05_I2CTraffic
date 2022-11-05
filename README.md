# ESE5190 Lab 2B Part 05 - I2C Traffic

## Lab 2B - Amogh Gajare worked with Saurabh Parulekar

[Link](https://content.arduino.cc/assets/Nano_BLE_Sense_av02-4191en_ds_apds-9960.pdf) to the Datasheet referenced in the document.



![](https://user-images.githubusercontent.com/38959831/200089514-eb981eba-d2c4-43b4-9531-d2a2ae6ddceb.jpeg)

![](https://user-images.githubusercontent.com/38959831/200091634-2d5b7305-a765-48c2-9acf-c4dac18761ff.jpeg)


![](https://user-images.githubusercontent.com/38959831/200091652-20074e86-0a74-4d86-9af2-e02b42fc00ed.png)

![image](https://user-images.githubusercontent.com/38959831/200091726-61dca78f-5549-469a-856f-6f724ff555b8.png)

According to the dataset APDS9960 supports only one slave address 0x39, which we can see it the annotated image.
Here, W=0, which means that it is in Write Mode
Acknowledge is 0
The register address we see here is 0x96, which is the RDATAL register, the low byte of Red Channel Data.




