# 快速集成 Recording SDK
1.获取agora sdk
1.将API Reference中的文件添加到您的项目中
2.将agora sdk的include中的头文件添加到您的项目中
3.链接agora sdk的so文件
4.根据API文档调用相关的API进行录制

# 录制 API Reference 简介
API Reference是基于agora sdk api完成的一套更高层API，以源码方式提供，目标是为了对齐老版本（官网版本）的API，方便使用老版本SDK的用户升级。
# 录制 API Reference 目录结构
**include**
base：一些基础的头文件
IAgoraLinuxSdkCommon.h：公共的基础结构体和枚举值
IAgoraRecordingEngine.h：录制引擎的接口类和配置信息

# API 参考
参考IAgoraRecordingEngine.h头文件注释

# example
video_mixer目录下是一个将合图录制的demo，规则是有新增用户就加入合图，最多合成一个九宫格。


（API Reference以源码方式提供，对于有更灵活使用需求的用户，可以直接参考
https://docportal.shengwang.cn/cn/server_gateway/API%20Reference/linux_server_cpp/index.html，调用low level api集成录制）
