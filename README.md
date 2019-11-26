# 黑苹果安装记录 MSI Z390 和 i9-9900K

微星 MSI Z390 GAMING PRO CARBON AC 华硕 Vega64 黑苹果

## 机器配置

主板：[微星 MSI MPG Z390 GAMING PRO CARBON AC](https://www.msi.com/Motherboard/MPG-Z390-GAMING-PRO-CARBON-AC)

CPU：[Intel i9 9900K](https://ark.intel.com/content/www/us/en/ark/products/186605/intel-core-i9-9900k-processor-16m-cache-up-to-5-00-ghz.html)

内存：Avexir DDR4 2400

显卡：[华硕 ASUS AREZ-STRIX-RXVEGA64-O8G-GAMING](https://www.asus.com/us/Graphics-Cards/AREZ-STRIX-RXVEGA64-O8G-GAMING/)

电源：[EVGA SuperNOVA 750 G+](https://www.evga.com/products/product.aspx?pn=120-GP-0750-X1)

散热：[MASTERLIQUID ML240R RGB](http://www.coolermaster.com/cooling/cpu-liquid-cooler/masterliquid-ml240r-rgb/)

固态：三星 970 EVO 500G

板载声卡：ALC S1220A

板载有线网卡：Intel I219V7

显示器：戴尔 P2715Q 4K显示器

机箱：[追风者 PK-515ETG](http://www.phanteks.com/Enthoo-Evolv-ATX-TemperedGlass.html)

## 安装过程

**重要提示：已降 BIOS 至 [Version 7B17v10](https://www.msi.com/Motherboard/support/MPG-Z390-GAMING-PRO-CARBON-AC)，不在卡 no nvram variable。**

1. [【黑果小兵】**macOS Mojave 10.14.3 18D42** 正式版 **with Clover 4859**原版镜像](https://blog.daliansky.net/macOS-Mojave-10.14.3-18D42-official-version-with-Clover-4859-original-image.html)
2. 执行：**300**系列主板请于**drivers64UEFI**目录中移除**AptioMemoryFix-64.efi**添加**OsxAptioFix2Drv-free2000.efi**该驱动位于**/EFI/CLOVER/drivers-off**目录下。顺利进入**macOS**安装界面
3. 系统后序安装和复制 **EFI** 到硬盘教程：[联想小新**Air 13**安装黑苹果兼**macOS Mojave**安装教程](https://blog.daliansky.net/Lenovo-Xiaoxin-Air-13-macOS-Mojave-installation-tutorial.html)
4. 进入系统设置页面前：卡在 **AppleUSBHostResources panic**。解决方案是**boot** 添加 **safe mode**
5. 合并 **Windows** 和 **Clover** 引导
6. 完善驱动
7. 结束



## 附图



![Hackintosh-i9 2019-03-15](https://gewill.org/assets/Hackintosh-i9%202019-03-15.png)

## 总结

1. 小兵教程很好用。
2. 就是一直卡在 BIOS 部分，所以无论做什么努力的都没有效果。所以购买主板一定要看 tonymacx86.com 的 [Buyer's Guide](https://www.tonymacx86.com/buyersguide/building-a-customac-hackintosh-the-ultimate-buyers-guide/) 和网友的成功贴。我只之前微星 Z170A M3 安装黑苹果成功，就想当然的买了微星的这块主板。活生生的因为 BIOS 问题，至少1个月的安装时间浪费了。
3. 买主板别买带无解的无线网卡，明明可以省200块，去买同系列的微星 MPG Z390 GAMING PRO CARBON。然后去买免驱的无线蓝牙网卡：Broadcom 94360CD。
