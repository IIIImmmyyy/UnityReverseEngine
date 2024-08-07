咳咳.给自己打个广告
## [Android U3D手游安全中级篇] 
## [https://github.com/IIIImmmyyy/u3dCourse](https://github.com/IIIImmmyyy/U3DGameCourse)

- [README 中文](./README.md)
- [README English](./README-en.md)
# UnityReverseEngine
Decompile APK/IPA  To  UnityProject 
<br/>
<br/>

**UnityReverseEngine**目前正处于开发阶段...

## 介绍
UREngine是一个反编译引擎。用于还原Unity打包后的**APK/IPA**工程，可将打包后的文件**逆转为Unity工程**，可直接在**Unity编辑器上二次开发，甚至无需改动即可运行**。
目前UREngine已经实现了对绝大部分汇编指令的解析以及和Il2Cpp的关联，可将Arm64指令完整的并且最贴近源码的形式直接生成.CS文件。**(UREngine的语义解析器会去除引擎的初始化代码和垃圾代码)**
<br/>

## 平台支持

- Android APK (Arm64)
- IOS IPA
- PC(待定)
<br/>

### Cpp2CS效果图

**原代码**：
<br/>
<img alt ="u3d.ong" src="https://raw.githubusercontent.com/IIIImmmyyy/UnityReverseEngine/master/source/ori.png" >
<br/>
**IDA**：
<br/>
<img alt ="u3d.ong" src="https://raw.githubusercontent.com/IIIImmmyyy/UnityReverseEngine/master/source/ida.png" >
<br/>
**Il2Cpp逆转为C#**：
<br/>
<img alt ="u3d.ong" src="https://raw.githubusercontent.com/IIIImmmyyy/UnityReverseEngine/master/source/back.png" >


## 等待开发
### Cpp2CS指令解析未完成部分：

- ~~VTable解析~~；( :smile: 简单，基本结束)
- Struct 类型参数解析 (局部引用比泛型还复杂 FK )；
- 引用计数去除垃圾代码；
- 泛型解析 (  :cold_sweat:  ...有点复杂,处理中 )；
- 未知.
### 资源部分；

- 组件与脚本的绑定关系关联；
- 未知.
   
