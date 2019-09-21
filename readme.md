�ù�����RM2019���״�ʦ�����������������˵�Ƕ��ʽ����ʹ�õ�оƬ�ͺ�Ϊstm32f427IIH6��ʹ��st��˾��׼�⡣

The project is the program for the embedded system for the Robomaster 2019 competition. The chip is stm32f427IIH6 that uses the standard library provided by STMicroelectronics.


Ŀ¼��Table of Contents

CMSIS���ں���ص��ļ� Files related to the kernel

FWLIB����׼���ļ� Standard library files

Project�������ļ� Project files

startup:оƬ�����ļ� Loading files when the chip boots

user���û���д������ļ�����Ҫ��д���ļ���������ļ����� Files written by developers. This should be the place the majority of your code.

user/main.c\h :main�������ڵ��ļ� The file that contains the main function

user/AHRS�������������Լ���̬���� Gyroscope driver and posture computation

user/APP��freeRTOS���� freeRTOS tasks

user/DSP��DSP�� DSP libraries

user/FreeRTOS:��ֲ��freeRTOS�ļ� Ported freeRTOS files

user/hardware��Ӳ���� Hardware layer

user/user_lib����д����ѧ���� Mathematical functions
