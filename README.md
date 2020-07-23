# USB-2.0-HUB
主控SL2.1A的HUB
PCB使用立创EDA设计，BOM和Gerber均已上传。
原理图和PCB文件为json文件（project压缩包内），可以用立创EDA打开，具体方法参见立创EDA使用教程https://docs.lceda.cn/cn/Export/Export-EasyEDA-Source-File/index.html
立创EDA调整等长比较不方便，差分线还有20~50mil不等的长度差，以后可能用AD重绘一次。

---------------7.24更新------------
AD重绘版的原理图和PCB已打包上传。
实物测试：
使用移动硬盘测试，读写均可达到42MB/s左右，算是把480Mb跑满一大半吧，二层板这样应该不错了（使用外部晶振）？
注意：
使用外部晶振的时候不要焊R2,使用内部晶振的话焊一颗0Ω电阻接地；
另外建议LED串联的R1选择2k以上的，不然的话会非常亮。当然，要根据实际的LED型号来选择电阻阻值。
