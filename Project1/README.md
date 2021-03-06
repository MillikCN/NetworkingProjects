# Project1

自行设计协议，实现在多台计算机/虚拟机之间模拟C/S通信和P2P通信。

## C/S通信

要求如下：

- 三台计算机/虚拟机分别模拟服务器、客户端；

- 通过Socket编程实现服务器端、客户端程序；

- 服务器端程序监听客户端向服务器端发出的请求，并返回数据给客户端；

- 如果client1与client2交换信息，如何实现？

- 不允许采用HTTP方式，自定义通信协议，传输文件要足够大（例如：一个视频文件）；

- 仅允许采用物理机或虚拟机的方式实现客户端与服务器端。

## P2P通信

要求如下：

- 为每个peer开发服务器程序、客户端程序；

- 每个peer上线后，向服务器注册自己的通信信息；

- 假设peer3要下载文件A（视频），peer1与peer2都拥有A，请设计方案使peer3能够同时从peer1、peer2同时下载该文件，例如：从peer1下载A的前50%、同时从peer2下载后50%。

- 如何以P2P的方式实现peer1,2,3相互聊天/视频会议，交换数据？

- 比较C/S与P2P通信方式的性能指标

- 仅允许采用物理机或虚拟机的方式实现peer与服务器。
