# FPGA-gyro-AWS
《摇摇乐（陀螺仪+AWS》，我们将基于SEA-7开发平台，利用开发板的板载陀螺仪资源读取姿态数据，采集到相关数据之后，计算得出一分钟之内开发板被摇动的次数，将次数数据发送给ESP32，并且通过ESP32的wifi联网和蓝牙功能，将数据上传至AWS云服务端口，最终完成摇摇乐的实现。
