![逐飞LOGO](https://images.gitee.com/uploads/images/2019/0924/114256_eaf16bad_1699060.png "逐飞科技logo 中.png")
# 逐飞科技STC8H8K64开源库
#### 简介
逐飞科技针对参加各类竞赛以及使用STC8H8K64进行产品开发，制作的STC8H8K64开源库。

#### 环境准备
1.  **STC8H8K64硬件环境：** 
- 推荐使用本公司STC8H8K64核心板，[点击此处购买](https://item.taobao.com/item.htm?spm=a1z10.3-c-s.w4002-22508770840.19.12dc49ccDFOaob&id=618018828966)。
2.  **软件开发环境：** 
（MDK FOR C51）
- MDK 推荐使用版本：V9.6。
3.  **下载器：** 
（核心板自带）
- 核心板自带有CH340E芯片，只需要插上TYPE-C数据线即可实现下载功能。
- USB转TTL：推荐使用本公司USB转TTL，[点击此处购买](https://item.taobao.com/item.htm?spm=a1z10.3-c-s.w4002-22508770840.9.12dc49ccL93dhG&id=524829874577)。
3.  **内部晶振频率：** 
- board.h文件中FOSC的值设置为0，则程序自动设置系统频率。
- board.h文件中FOSC的值设置不为0，则系统频率为FOSC的值。在使用stc-isp工具下载程序的时候需要将IRC频率设置为FOSC的值。

#### 使用说明

1.  **下载开源库：** 点击页面右侧的克隆/下载按钮，将工程文件保存到本地。您可以使用git克隆（Clone）或下载ZIP压缩包的方式来下载。推荐使用git将工程目录克隆到本地，这样可以使用git随时与我们的开源库保持同步。关于码云与git的使用教程可以参考以下链接 [https://gitee.com/help](https://gitee.com/help)。
2.  **打开工程：** 将下载好的工程文件夹打开（若下载的为ZIP文件，请先解压压缩包）。在打开工程前，请务必确保您的IDE满足环境准备章节的要求。

#### 逐飞科技STC8H8K64核心板
![逐飞科技STC8H8K64核心板](https://images.gitee.com/uploads/images/2020/0601/161506_e9a42fea_848799.jpeg "逐飞科技STC8H8K64核心板.jpg")


