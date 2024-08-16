## OCEFI
适用于 x58 平台的 OpenCore 配置

## 测试配置
### 系统
x58 杂牌主板，咸鱼
![主板](https://pic.imgdb.cn/item/66bee56ed9c307b7e94a3d90.jpg)


志强 x5650，6c12t，2.66，95W
![x5650](https://pic.imgdb.cn/item/66bee5c4d9c307b7e94a80b2.jpg)


16G 双通道混搭 ECC 内存
![内存](https://pic.imgdb.cn/item/66bee64fd9c307b7e94ae3fe.png)


256G SATA 固态，512G 机械
![硬盘](https://pic.imgdb.cn/item/66bee6a5d9c307b7e94b2b9a.png)

### 显卡
HD7750，接 DVI
![显卡](https://pic.imgdb.cn/item/66bee56ed9c307b7e94a3dcd.jpg)
![接口](https://pic.imgdb.cn/item/66bee56ed9c307b7e94a3de0.jpg)

### 网卡&蓝牙
BCM943602cs，三天线，蓝牙占前置 USB 借口返还一个 USB2.0
![网卡](https://pic.imgdb.cn/item/66bee56fd9c307b7e94a3e12.jpg)

### 声卡
板载 ALC662，alcid=5
![声卡](https://pic.imgdb.cn/item/66bee769d9c307b7e94bce25.png)


## 完成度
- [x] 显卡 Metal 加速驱动
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

