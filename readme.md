# Test setup Proteus 3 Modules

# Config

- Connect both Proteus 3 Modules 
- Chose COM Port
- Start Labview TestTool
- Configure Module to "Just Works Level 1.2"

![01_configure](./doc/pic/01_configure.png)



This configures Module to  "Just Works Level 1.2" as shown in the Datasheet below

![securityflags](./doc/pic/securityflags.png)



## scan

Scan for available devices with following steps

- scan start
- scan stop
- scan getdevices

![02_scanstart](./doc/pic/02_scanstart.png)

![03_scanstop](./doc/pic/03_scanstop.png)

![04_getdevice](./doc/pic/04_getdevice.png)



## connect/tx/rx/disconnect

Execute following steps

- connect 
- send data
- (receive data)
- disconnect

Limitation; the module multiple connections at the same time. But it will be possible to control multiple modules at the same time.

![05_connect](./doc/pic/05_connect.png)

![06_send](./doc/pic/06_send.png)

![07_receive](./doc/pic/07_receive.png)

![08_disconnect](./doc/pic/08_disconnect.png)