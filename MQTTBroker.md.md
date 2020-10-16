## MQTT Broker:
1.Install using  link: " https://mosquitto.org/files/binary/win64/mosquitto-.6.12-install-windows-x64.exe"
2.Select the installation path : "C:\programfiles\mosquitto"
3.Copy the path
4.This PC>Right click>properties>Advanced system settings>environmnet variables>path>new>paste the copied path
5.Open command prompt and type "mosquitto -v"

![mosquitto.png](/.attachments/mosquitto-17bc6605-54d6-4238-8815-a203ccf19472.png)
6.to run mosquitto as service: "mosquitto -v -p 666"