# WebRTC

## WebRTC

- Open Source(Google)
- cross-platform
- For the browser
- live transmission(实时传输)
- Audio and video engine(音视频引擎)

## 流媒体服务器

- 信令服务器
  - 信令处理
  - WebSocket
- 数据处理
  - 逻辑处理
  - SRTP
  - RTP
  - RTMP
- 客户端
  - 浏览器
  - Android
  - iOS
  - PC
  - Mac
- 网络
  - 3G
  - 4G
  - 5G

## 应用流媒体服务器

- 在线教育
- 远程医疗
- 多协议融合
- 音视频会议
- 多个互动游戏
- 直播连麦
- 即时通信
- 多终端融合

## 流媒体特点

- 技术难度大、门槛高
- 涉及的指点多
- 系统的资料少
- 网上Demo调不通

## 课程体系

- 1. 基础知识
    - C++基础
    - 网络 socket
- 2. 网络传输协议
  - TCP
  - UDP/RTP
  - 实时传输应该用哪种底层协议
  - RTP协议的使用 
- 3. 高性能网络编程
  - select 异步I/O 事件处理
  - epoll 异步I/O 事件处理
  - libevent 处理异步 I/O事件
  - libuv 处理异步 I/O 事件
- 4. WebRTC 协议栈
  - STUN/DTLS/SRTP
  - 数据安全与OpenSSL
  - SDP 与媒体协商
 - 5.音视与通话
  - 多人实时通信
  - mediasoup 整体架构
  - mediasoup 与浏览器对接
  - 音视频数据的流转
  - mediasoup 使用各种传输协议 

## Compile C++ in MAC

`$ clang++ -std=c++11 -g -o hello hello.cpp`