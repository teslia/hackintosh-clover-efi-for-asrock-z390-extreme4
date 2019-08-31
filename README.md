# hackintosh-clover-efi-for-asrock-z390-extreme4
Asrock Z390 Extreme4 Clover EFI files.

EFI 用于 10.14.6 测试可以正常使用。
以下版本也测试通过   
10.14.5   

OSX Tested:   
10.14.6   
10.14.5   

## 重要说明！ Attention!
请使用Clover Configurator修改config.plist中的序列号！
You must use Clover Configurator to modify the serial number in config. plist!

## 已测试项目
- [x] CPU变频
- [x] 显卡硬件加速(QE/CI)
- [x] 板载ALC1220 音频输出 
- [x] DisplayPort 视频/音频输出
- [x] USB3.0 USB2.0
- [x] 有线网卡
- [x] 睡眠和唤醒

## 我的配置 My hardware list
- Intel Core I9 9900k
- Lexar SSD 480G NVM.e
- DDR4 2666 8G x4 
- VP2780 4K Display use DisplayPort

## Bios Set:	
1. Load UEFI Defaults	
2. Advanced	
    - CPU Intel Virtualization Technology: Enabled	 
    - VT-d: Disabled	
    - Onboard HD Audio: Enabled	
    - CSM： Disabled
    - USB Configuration, XHCI Hand-off, Enabled	
    - Super IO Configuration, Disabled	
3. Security	
Secure Boot, Disabled(by default)	
