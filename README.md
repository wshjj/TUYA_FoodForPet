This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.         For more information, please check Tuya Developer Website.
## 一、方案标题
涂鸦宠物喂食器
## 二、方案应用场景
地点：用户家中  
功能：  
1. 可以自动添加食物，也可以远程手动添加食物；添加食物通过电机完成，可以在手机上设置时间定时投喂，也可以手机上点击后立即投喂。  
2. 可以检测宠物食物余量，返回到用户手机；利用称重传感器称量剩余食物余量，将检测到的食物质量传输到手机，帮助用户了解还剩多少食物。  
3. 还能远程打开小夜灯，故障报警等。
## 三、技术方案
主控选择STM32F103C8T6单片机，外设包括添加食物所需的电机，称量食物余量所需的称重传感器（可能还需要配备差分放大ADC模块），提示以及报警所需的LED灯和蜂鸣器。  
通过涂鸦的联网模组将单片机搜集的质量数据，报警信息上传至手机；或者手机上选择投食，则发送信号至单片机，单片机输出驱动电机信号开始投食，投到一定食物或者投满后停止。
## 四、开发计划
3月28日前完成  
1）3月15日前准备物料  
2）3月16日至3月23日嵌入式开发  
3）3月28日前整体调试
