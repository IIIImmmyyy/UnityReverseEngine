# UnityReverseEngine
Decompile APK/IPA to UnityProject

**UnityReverseEngine** is currently under development...

## About UREngine
UREngine is a decompiling engine designed to restore Unity-packaged **APK/IPA** projects, converting them back into Unity projects. This allows for direct re-development in the **Unity Editor**, and the projects can even run without modifications. UREngine has achieved significant progress in parsing most assembly instructions and linking with Il2Cpp, generating .CS files that closely resemble the original source code. **(UREngine's semantic parser removes initialization code and junk code from the engine)**

## Platform Support

- Android (Arm64)
- iOS (Arm64)
- PC (To be determined)

### Cpp2CS Conversion Example
**Original Code**:
![Original Code](https://raw.githubusercontent.com/IIIImmmyyy/UnityReverseEngine/master/source/ori.png)

**IDA**:
![IDA](https://raw.githubusercontent.com/IIIImmmyyy/UnityReverseEngine/master/source/ida.png)

**Il2Cpp Reversed to C#**:
![Il2Cpp to C#](https://raw.githubusercontent.com/IIIImmmyyy/UnityReverseEngine/master/source/back.png)

## Pending Developments
### Unfinished Parts of Cpp2CS Instruction Parsing:

- VTable parsing;
- Parsing of Struct type parameters;
- Removal of junk code through reference counting;
- Generic parsing;
- Unknown.

### Resource Section:

- Association of components and scripts;
- Unknown.
