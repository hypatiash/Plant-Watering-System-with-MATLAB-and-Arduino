# Plant-Watering-System-with-MATLAB-and-Arduino

### Requirements of the Project
The general working principle of the app is, if the moisture percentage of the soil is under the determined threshold, the water pump starts watering the soil. If the soil moisture percentage is above the threshold, nothing happens.

### App Interface
The overall interface is shown below. User can select time duration by entering numerical value in the duration part. 
Threshold can be selected as 10, 20, 30, 40, 50, 60 ,70, 80, 90, 100. When Plot Button pressed, moisture and threshold line can be seen in the axes. Line properties for moisture percentage and threshold can be changed with the elements that placed bottom of the interface. User can save file as .jpg, .png, and .fig. 
![image](https://github.com/hypatiash/Plant-Watering-System-with-MATLAB-and-Arduino/assets/142400240/3578c0f4-edc2-4ccb-a685-93f6f7f1903d)

### Setup 
Used materials are, Arduino Uno, water pump, humidity sensor, breadboard and BC238 transistor.
![image](https://github.com/hypatiash/Plant-Watering-System-with-MATLAB-and-Arduino/assets/142400240/91ddac05-288f-4a92-8638-2017469939c2)

### Sample demonstration of the application
Below image demonstrates the threshold value as a 40 and moisture percentage as an approximately 65. Since moisture percentage above the threshold value, water pump does not need to work.
![image](https://github.com/hypatiash/Plant-Watering-System-with-MATLAB-and-Arduino/assets/142400240/095edb4c-997c-4499-aac2-b8636df14b2c)

 Below image demonstrates the threshold value as 70 and moisture percentage value as approximately 65. After some time, to achieve moisture percentage value as 70, water pump will start to run.
 ![image](https://github.com/hypatiash/Plant-Watering-System-with-MATLAB-and-Arduino/assets/142400240/b441bb70-e98c-4c52-8062-d5d28a84c9e8)

As you can see the below image, when we set the threshold value to a 30 and 70 respectively, moisture percentage value increases as well.
![image](https://github.com/hypatiash/Plant-Watering-System-with-MATLAB-and-Arduino/assets/142400240/d64b748c-5384-4a4c-9183-83c9fc009460)
