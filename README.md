#### DavlinkOpcodes.txt

该文件为opcode词典，脚本中首先加载该文件，随后将提取出的opcode映射为词典中对应的十六进制数。

---

#### get_opcode_sequence.py

该文件为opcode提取脚本，可自动遍历指定目录中的所有apk文件，并将其提取出的opcode sequence文件按照apk文件名输出到指定目录中，该脚本运行需要```apktool```支持。

---

该脚本来自开源项目：

- <https://github.com/niallmcl/Deep-Android-Malware-Detection>
- 阅读整理过程中加了一些参数注释，可能看起来有些乱，见谅，原始文件可在上述项目中找到。