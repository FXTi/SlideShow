# 逆向工程核心原理

第一章～第四章

---

## 第一章

关于逆向工程

---

### 逆向工程

逆向工程(Reverse Engineering，简称RCE)一般指，通过分析物体，机械设备或系统，了解其结构，功能，行为等，掌握其中原理并改善不足之处，添加新创意的一系列过程。

---

### 逆向分析法

* 静态分析法

* 动态分析法

---

#### 静态分析法

在不执行代码文件的情形下，对代码进行静态分析的一种方法。通过观察代码文件的外部特征，获取文件的类型(EXE,DLI,DOC,ZIP等)，大小，PE头信息，Import/Export API，内部字符串等等。

使用反汇编工具查看内部代码，分析代码结构也属于静态分析的范畴。静态分析得到的信息是动态分析的重要参考资料。

---

#### 动态分析法

在程序文件执行过程中对代码进行动态分析的方法，在调试中分析代码流，获取内存状态等。还能看到程序运行时与注册表，网络流等交互情况。常使用调试器分析内部结构和动作原理。

灵活使用静态与动态两种分析方法可以提高分析效率。

---

### 程序的常见形态

* 源代码

* 十六进制代码

* 汇编代码

善用Google

---

## 逆向分析Hello World!程序

就像写程序会输出"Hello World"一样，我们从这个小例子开始。

---

### OllyDBG

* Ctrl+F2

* Ctrl+G

* F2

* F4

* F7

* F8

* Ctrl+F9

---

### 起步

* 入口点(Entry Point -- EP)

* 启动函数

* 查找main()函数

---

### 快速定位main()函数

* 代码执行法

* 字符串检索法

* API检索法：在调用代码中设置断点

* API检索发：在API代码中设置断点

---

### 通过“打补丁”修改"Hello World"字符串

“打补丁”





- Dispatcher: Manages Data Flow
- Stores: Handle State & Logic
- Views: Render Data via React

---

![Flux Explained](https://facebook.github.io/flux/img/flux-simple-f8-diagram-explained-1300w.png)
