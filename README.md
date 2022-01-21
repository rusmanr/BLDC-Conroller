# BLDC-Conroller
This is a controller for ZLTECH ZLAC8015D dual motor BLDC driver

Written in Qt 5.15 C++ tested on Ubuntu and Windows (plan)

the command is sent using MODBUS RTU protocol

we implement is only dealing with velocity since it is intended to drive Autonomour Mobile Robot

Later the code will be ported to ROS2 package.

this code is base on **QModBus_RTU** https://github.com/Kefir0192/QModBus

and http://www.libmodbus.org
