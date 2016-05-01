# 安妮机械键盘

[官方网站][anne-link] | [京东众筹][anne-jd-z-link] | [淘宝店铺][anne-taobao-link]

> 安妮键盘是由 obins 是由一群程序猿、设计师和外设发烧友一同打造的外设品牌。
> o是our的首字母，代表着程序猿、设计师、发烧友、粉丝等喜欢obins产品的所有生物体，
> bin 在计算机中表示程序本身，在物理世界中代表我们的产品，obins 就是大家共同创造的产品，
> 希望用最用心的设计，为用户提供最完美的产品和体验。

## 声明

这是一份非官方收集的关于安妮机械键盘的相关资料，主要目的是为了方便使用者能够找到一个相对比较全的地方查阅资料。

## 沟通交流

- 键盘群 `478061089`
- 固件群 `340574284` - 需校验键盘群是否已加

## 版本

- 安妮标准版
- 安妮 Pro 版

### 详细参数和区别

这是一款 60% 键机械键盘

名称 | 标准版 | Pro 版
---|---|---
按键数量 | 61 | 61
主控 | STM32L151 | STM32L151
USB/PS2 | 支持 | 支持
响应时间 | 1ms | 1ms
硬件去抖动 | 支持 | 支持
外壳 | 彩色外壳 | 彩色外壳
键帽 | PBT 双色注塑透光 | PBT 双色注塑透光
固件升级 | 支持(PC) | 支持(App)
蓝牙4.0 |  无 | **支持**
App支持 | 无 | **支持**
独立灯光IC | 无 | **支持**
灯效 | 单色灯效(红) | **RGB 1600万色**
拔键器 | 有 | 有
USB连接线 | 有 | 有
蓝牙适配器 | 无 | **有**

## 快捷键

快捷键 | 描述 | 备注 | 版本要求
---|---|---|---
FN + U | 切换灯效（单循环） | 先静态在动态
FN + Y | 调整灯光亮度（单循环） | 10 级亮度
FN + T | 动态灯效速率||
FN + B | 蓝牙适配 | 详情看[PDF][anne-manaul-link]
FN + - | 关闭蓝牙 | | v1.0a
FN + R | 一键关灯 | | v1.0a
FN + 0 | 兼容模式/标准模式切换 | 黄灯表示兼容模式，绿灯为标模式 | v1.0a


## 按键布局（配列）

### 标准布局1

> 系统预置布局

快捷键 | 描述
---|---
FN + WSAD | 上下左右
FN + IKJL | 上下左右
FN + ? | Delete
FN + > | Insert
FN + ; | Page Up
FN + ' | Page Down
FN + [ | Home
FN + ] | End
FN + \ | Print Screen
FN + 123456789 | 功能键 F1-9
FN + 0 | 功能键 F10
FN + - | 功能键 F11
FN + = | 功能键 F12

### 标准布局2

> 带独立方向键的标准布局

### Mac 布局

> Mac 标准布局

## 固件版本

- `正式版` 版本号以偶数结尾的
- `测试版` 版本号以奇数结尾的

### [升级固件说明书][anne-dfu-manaul-link]

### 版本列表

版本[变更历史][anne-dfu-changelog-link]

#### 正式版

版本号 | 发布时间
---|---
[1.0a](dfu/stable/v1.0a.rar) | 2016.04.30

#### 测试版

版本号 | 发布时间
---|---
[1.09.03](dfu/beta/v1.09.03.rar) | 2016.04.30


[anne-link]: http://www.obins.net/
[anne-jd-z-link]: http://z.jd.com/project/details/34676.html
[anne-taobao-link]: https://shop116784704.taobao.com/

[anne-dfu-changelog-link]: dfu/CHANGELOG
[anne-manaul-link]: files/安妮PRO使用须知1.pdf
[anne-dfu-manaul-link]: files/固件升级简易说明书.png
