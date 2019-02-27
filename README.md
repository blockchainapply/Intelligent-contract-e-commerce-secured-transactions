#noobchain

#### 项目介绍
基于智能合约的电子商务担保交易简单实现

#### 软件架构
无

#### 安装教程

1. Eclipse Jee 2018-12
2. jdk-8u201-windows-x64
3. gson-2.6.2.jar

运行环境jdk1.8+ 版本
配置环境变量
右键 此电脑——属性——高级系统设置-高级
——环境变量
找到安装java SDK的目录，复制该路径
点击‘系统变量’ 下的新建
变量名处填写‘JAVA_HOME', 变量值处直接粘贴,然后点击"确定"
在在“系统变量”点击“新建”，在弹出的窗口中分别输入变量名：”CLASSPATH”变量值: “.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar;”（取引号之内的值，包括前面的”.” ，这里%JAVA_HOME%就是引用之前配置好的 JAVA_HOME ）
在Eclipse 中建立一个新的Java project
(file > new > ) Java project
在这里我们把它命名为noobchain
用同样的名称建立一个新的类Noobchain

GSON是Google提供的用来在Java对象和JSON数据之间进行映射的Java类库。
我们需要从google上下载Gson Jar ( “gson-2.6.2.jar” ) 
并记录你的保存路径
在Eclipse menu里打开Windows >preferences, 选择Java >Build path > User Libraries. 点击 new 建立一个新的User Library 取名为 “gson_lib” 点击确认. 
选中gson_lib，按右边添加外部的JARs找到你存的gson-2.6.2.jar 应用并关闭
添加User Libarary到你的java project中: 右键你的java projact的package选择 package explorer > Build path > Add Libraries. 
选择User Libraries中你新建的 “gson_lib” 然后点击结束


#### 使用说明

启动类Noobchain.main（） 运行程序

#### 参与贡献
15124426 万晓婷
15124429 张晨曦
15124485 马丽娅
16124301 范代千  	



