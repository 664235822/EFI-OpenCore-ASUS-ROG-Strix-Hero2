# EFI-OpenCore
华硕玩家国度ROG魔霸2自用黑苹果OpenCore引导

## 我的机型
* Asus ROG Strix Hero II GL504GM
* 机型选择 MacBookPro15.3

## 我的配置
* CPU：Intel Core i7-8750H，3900MHz
* 内存：16 GB 2667 MHz DDR4
* 集成显卡：Intel(R) UHD Graphics 630 (1 GB)
* 独立显卡：GeForce GTX 1060 (6 GB)
* 声卡：Realtek ALC294
* 无线网卡：Intel(R) Wireless-AC 9560
* 有线网卡：Realtek RTL8111H PCI Express Gigabit Ethernet

## 黑苹果安装情况
* CPU变频正常
* 集成显卡已驱动
* 独立显卡已禁用
* 声卡驱动成功（id=21）
* 外放耳机切换正常，但是切换回外放后会有爆音
* 无线网卡已驱动，支持原生Wifi管理
* 有线网卡已驱动
* 蓝牙正常（可正常开关）
* 亮度调节正常
* 亮度调节快捷键未正确映射
* 触摸板已驱动
* 电池驱动已正常
* 睡眠唤醒无解，会立即唤醒
* 已开启原生NVRAM
* 已支持USB3.0，最快速度达5Gbps
* 引导菜单使用官方主题

## 使用方法
* 设置的是自动启动，查看选项请在启动时一直按Alt键
* 声卡无声音的请设置BIOS`Advanced->Animation Post Logo Configuration->Animation Post Logo Audio`为`Disabled`
