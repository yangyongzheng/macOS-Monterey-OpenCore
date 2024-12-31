# macOS-Monterey-OpenCore
##  OpenCore

官方文档：[OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

##  硬件

主板：技嘉 `GA-B150M-D3H`

CPU：QuadCore Intel Core i5-6500, 3200 MHz

Graphics：核显 `Intel HD Graphics 530` ，主板 `HDMI` 口输出

Audio：`Intel Skylake HDMI` 、 `Realtek ALC892`

Ethernet：Intel Ethernet Connection (2) I219-V

##  安装

1. BIOS 设置
2. **设置U盘UEFI分区为首选启动引导盘**
3. 重启电脑选择 `Install macOS Monterey` 选项准备安装
4. 加载完成后，选择**磁盘工具**格式化磁盘为 `APFS` 和 `GUID` 分区
5. 磁盘格式化完成后回到安装页面继续安装即可
6. 安装完进入系统后，把U盘EFI拷贝到系统磁盘EFI分区
7. BIOS设置电脑磁盘UEFI分区为首选启动引导盘

##  问题

睡眠黑屏无法唤醒
