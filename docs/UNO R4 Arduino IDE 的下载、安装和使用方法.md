# UNO R4 Arduino IDE 的下载、安装和使用方法

## 1. 下载&安装IDE

1\. 首先，我们需要下载Arduino IDE，进入网页链接：[https://www.arduino.cc/en/software](https://www.arduino.cc/en/software) 下载，根据不同的系统下载对应的Arduino IDE最新版本。

![图片不存在](./media/261d08149500f0a0a84c404966e86b99.png)

2\. 在电脑上安装Arduino IDE。

3\. 打开 Arduino IDE

![图片不存在](./media/07ae486c48f0747c4aa8d9689045bdb4.png)

![图片不存在](./media/60db86b0ed51131fe9e87018c6feffc0.png) -- 用于检查是否存在任何编译错误。
![图片不存在](./media/b2193d5043fba0009d9990fbd1950612.png) -- 用于将程序上传到Arduino板。
![图片不存在](./media/fee2bce952fc3268b5ffe83c43e988a1.png) -- 用于编写程序时的单步调试。
![图片不存在](./media/355545db0e0d29f449328dae66723cdd.png) -- 用于从板接收串行数据并将串行数据发送到板的串行监视器。
![图片不存在](./media/2b5c0bc87aad42034edca51d9c4f8d35.png)-- 用于串口接收的数据转换成动态曲线图。
![图片不存在](./media/8bda2766b089260065f10d9552683904.png)-- 用于打开最近保存的示例草图。
![图片不存在](./media/0f790400df5391987fa77b25c8c4728e.png)-- 用手动安装开发板。

## 2. 安装主板包

1\. 要安装主板包，从左侧菜单中打开“开发板管理器”。搜索“UNO R4” 并安装最新版本(或你想使用的版本)。

![图片不存在](./media/033a7baabb4f661bd853c11e866e91ca.png)

2\. 单击“工具” → “开发板”，你现在能够看到Arduino UNO R4 boards 后面分有开发板类型：“Arduino UNO R4 WiFi”和“Arduino UNO R4 Minima”。

![图片不存在](./media/ecc749c3cbee720973a40e7333d06c47.png)

如果你将你的UNO R4 WiFi主板通过USB数据线连接到计算机，你可以看到如下所示：

![图片不存在](./media/3b80f771aa03a71df633e2da7b28d9d6.png)

![图片不存在](./media/f6101b91304c82af8f1b63df94a949f5.png)

如果你将你的UNO R4 Minima主板通过USB数据线连接到计算机，你可以看到如下所示：

![图片不存在](./media/03de6c39d4db997107b9f5f0e8b810ce.png)

![图片不存在](./media/185e1345ab9b764f0ac478a4fbb6480f.png)

## 3. 编译&上传草图

可以直接在IDE中通过“文件”→“示例”→“01 Basics”→“Blink”访问，这个例子不需要外部库就可以直接使用。

![图片不存在](./media/b9ef5dc0738742e4a04695ed04341798.png)

将你的UNO R4 WiFi主板通过USB数据线连接到计算机，选择好“Arduino UNO R4 WiFi”和端口。然后点击![图片不存在](./media/b2193d5043fba0009d9990fbd1950612.png)将程序代码上传至UNO R4 WiFi主板上，上传成功后，UNO R4 WiFi主板上的L灯闪烁。

![图片不存在](./media/fccf8080fde1b4187157e7d23097e398.png)

![图片不存在](./media/fa6f14c35c289dc84fab26eca0442fa0.png)

编译&上传草图至UNO R4 Minima主板上的方法类似，就不重复讲解。












