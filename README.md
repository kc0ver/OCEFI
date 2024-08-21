## OCEFI
适用于 x58 平台的 OpenCore 配置

## 测试配置
### 系统
安装 macOS 12.7.6，x58 主板，

![主板](https://github.com/user-attachments/assets/123c97ff-25d0-4f43-bdb1-c813115b766c)


志强 x5650，6c12t，2.66，95W

![x5650](https://github.com/user-attachments/assets/1626947e-680b-4744-b58e-5d937add1271)


16G 双通道混搭 ECC 内存

![内存](https://github.com/user-attachments/assets/980b84f0-4ec2-4bc5-9fbb-4f0db9dcaeee)


256G SATA 固态，512G 机械

![硬盘](https://github.com/user-attachments/assets/14331c06-b019-4a69-b4e5-46173f037f4a)


### 显卡
HD7750，接 DVI

![显卡](https://github.com/user-attachments/assets/2dd88331-ff91-4444-b592-99aff8d8c033)
![接口](https://github.com/user-attachments/assets/66196a18-adfb-4516-b27b-f6127638cf5f)


### 网卡&蓝牙
BCM943602cs，三天线，蓝牙占前置 USB 接口返还一个 USB2.0

![网卡](https://github.com/user-attachments/assets/3de2a036-02dc-4998-a873-064959ad0e06)


### 声卡
板载 ALC662，alcid=5

![声卡](https://github.com/user-attachments/assets/a7956a38-0e0a-4f73-933f-b6eab5414860)


## 完成度
- [x] 显卡驱动
- [x] 网卡&蓝牙驱动成功
- [x] 隔空投送&接力
- [x] 声卡驱动
- [x] 超线程支持
- [x] 硬盘内置
- [x] USB 2.0

## 问题
- [x] 关机不断电（DSDT 解决）
- [x] OOBE 链接 wifi卡死（进桌面再连解决）
- [ ] 自带输入法卡顿 Bug（疑似显卡问题） 
- [ ] 视频显卡解码加速
- [ ] 音响声音较小（不一定会复现）
- [ ] 画面偶尔撕裂
- [ ] 关机/重启卡屏（不是卡死）
- [ ] 蓝牙信号不好（网卡缺陷）
- [ ] **版本更新之后第一次启动卡锁屏（卡死）**

## 关于自带输入法卡顿
这个问题也会出现在 GT710 + 10.15.7 上，HD7750 + 10.15.7 就不会出现这个问题。

举个例子来说明这个卡顿：

我的名字叫做夏克，当我在键盘上输入“xia”拼音时，会有明显卡顿，候选字框显示正常。若连续输入“k”时，表现为候选框消失，输入框中为“xiak”字母，之后无论输入任何字母，候选框都不会出现。若清除输入框中所有文字，输入法候选框可再次出现，但仍表现为以上异常状况。






