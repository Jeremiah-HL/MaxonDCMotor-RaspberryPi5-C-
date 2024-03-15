# ReadMe
这是一个使用树莓派以及Maxon直流电机构建的项目，用以操控多自由度的机器人。
使用的设备是树莓派5，EPOS4 CAN Compact以及Maxon DC motor。如果你有一个DC电机，那么电机的型号任意即可。
使用C++编程语言，使用了wiringPi库，EposCmd库来构建项目。
- wiringPi：我的版本是3.01，我推荐使用github上的源码进行安装构建。
- EposCmd：这个库是由瑞士Maxon来提供的，具体库既可以在互联网搜索获得，也可以参考我的MaxonDCMotor-Cpp这个仓库中的一个文件夹（EPOS-Linux-xxx）来获取