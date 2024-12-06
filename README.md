# 跨平台gRPC IPC Protocol Buffers 定义

## 简介
本仓库包含了用于定义通过gRPC进行进程间通信（IPC）的服务和消息的Protocol Buffers (.proto) 文件。这些定义在服务器和客户端之间共享，确保消息传递的一致性。

## 使用方法
使用本仓库中的 `.proto` 文件通过Protobuf编译器为您的目标语言生成存根代码。

## 相关仓库
了解整个项目的其他组件，请访问以下仓库：
- Android客户端实现：[crossplat-grpc-ipc-android-client](https://github.com/JackieLeee/crossplat-grpc-ipc-android-client)
- Go服务端实现：[crossplat-grpc-ipc-go-service](https://github.com/JackieLeee/crossplat-grpc-ipc-go-service)