# UnityReverseEngine
Decompile APK/IPA  To  UnityProject 
<br/>
<br/>

**UnityReverseEngine**目前正处于开发阶段...

## 介绍
UnityReverseEngine是一个反编译引擎。用于还原Unity打包后的**APK/IPA**工程，可将打包后的文件**逆转为Unity工程**，可直接在**Unity编辑器上二次开发**。
目前UREngine已经实现了对汇编指令的逆转，可将Arm64指令完整的并且最贴近源码的形式直接生成.CS文件。**(UREngine的语义解析器会去除引擎的初始化代码和垃圾代码)**
<br/>

## 平台支持

- Android (Arm64)
- IOS (Arm64)
- PC(待定)
### 效果图
**原代码**：
<img alt ="u3d.ong" src="https://raw.githubusercontent.com/IIIImmmyyy/UnityReverseEngine/master/source/ori.png" >


**Il2Cpp逆转为C#**：
<img alt ="u3d.ong" src="https://raw.githubusercontent.com/IIIImmmyyy/UnityReverseEngine/master/source/back.png" >


## 等待开发
### Cpp2CS指令解析未完成部分：

- VTable解析；
- Struct 类型参数解析；
- 引用计数去除垃圾代码；
- 泛型解析；
- 未知.
### 资源部分；

- 组件与脚本的绑定关系关联；
- 未知.
   