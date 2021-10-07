控制器
=========

为什么使用ESP32
---------------
ESP32是一个开源的，集成了WIFI+Bluetooth的Soc。ESP32开发板性价比高，具有丰富的接口，
适合物联网产品和网络应用的开发。基于ESP32的案例众多，非常适合学生学习使用。


三路单色温控制器
--------------------------

功能：结合ESP开发板，控制单色温摄影灯亮度。

输入接口： 1路24V 直流输入，额定功率150W

输出接口： 3路PWM 24V直流输出，单路最大电流5A

控制方式： HOMEKIT APP或WEB

.. image:: /image/3M2P.png



两路双通道控制器
----------------
功能：结合ESP开发板，组成2路2通道控制器，从而控制2个双色温摄影灯。

输入接口：1个24V DC输入

输出接头：2个3Pin航空插头，单路最大5A

控制方式：HomeKit APP或网页控制

.. image:: /image/2m3p.png

RGB控制器
------------------------
应用推荐：*HOME KIT以及ESPHOME的编程学习*

功能：结合ESP开发板，可控制1个RGB灯，1个单色温灯以及一个12V散热风扇。

输入额定功率	150W（总）

输入电压：24V DC

外置天线：2.4G WIFI

适配：ESP32 DEV KIT官方开发板
	
DC标准端子输出：1个；
输出电压：24V；
功率：120W；
亮度调节：PWM


4端口输出：
1个 5.08 4pin端子；
功率	120W；
电压	12-24V；
Pin 1	正极；
Pin 2-4	负极（PWM）

接口类型	
3 pin 2.54mm 接口；
正极	12V DC；
负极	1个；
速度调节	PWM


4路0-10V控制器 4M10v 
----------------------------
功能：结合ESP开发板，可控制4路0-10v电压输出。适用控制大功率可调LED电源。

输入：1个24V DC输入

输出：4路DC直流电压输出

控制方式：HomeKit APP或网页控制

.. image:: /image/4M10V.jpg

.. youtube:: RQOhrgRd7N8

.. raw:: html

<iframe width="560" height="315" src="https://www.youtube.com/embed/8EEVPVNJHjM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>