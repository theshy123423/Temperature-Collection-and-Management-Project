# Temperature-Collection-and-Management-Project

<img width="1116" height="508" alt="下位机架构" src="https://github.com/user-attachments/assets/1d88e550-0232-429c-84bb-17a656fb9cf6" />
<img width="2280" height="1240" alt="服务器架构" src="https://github.com/user-attachments/assets/b0b52cf7-a992-48d4-9faf-b2eeb4af372d" />
<img width="1835" height="758" alt="客户端实现逻辑" src="https://github.com/user-attachments/assets/520e6c94-a727-4e33-b655-b5a7ba27f00b" />
使用 QT 完成客户端的用户登录界面以及温度显示界面的编写，使用 MQTT 协议获取下位机实时的温度，使用 HTTP 协议实现登录验证、历史数据统计、设备在线状态、设备控制等数据的传输。在 Linux 下完成服务端的编写，通过 MQTT 和 HTTP 协议完成与客户端相关数据的交互，并把所有数据都写入 Mysql 数据库，通过 UART 串口通信完成与下位机的通信，下位机使用 STC15 单片机的 DS18B20 获取环境温度。
