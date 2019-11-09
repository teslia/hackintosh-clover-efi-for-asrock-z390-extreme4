# hackintosh-clover-efi-for-asrock-z390-extreme4
华擎Z390 极限玩家4 黑苹果EFI文件    
Asrock Z390 Extreme4 Clover EFI files    
BIOS Version: 4.20     

## 已测试OSX版本 OSX Tested   
##### Catalina    
    
10.15

##### Mojave      
*分支未测试，如果有问题请使用10.14分支！*     
*The master branch is NOT Tested，Please use `10.14` branch if not work.*      
    
10.14.6     
10.14.5    

## 重要说明！ Attention!
请使用Clover Configurator修改config.plist中的序列号！     
You must use Clover Configurator to modify the serial number in config. plist!

## 已测试项目
- [x] CPU变频
- [x] 显卡硬件加速(QE/CI)（Intel UHD Graphics 630 OK）
- [x] 板载ALC1220 音频输出  （ALC1220 Soundcard OK）
- [x] DisplayPort 视频/音频输出 （DP OK）
- [x] USB 2.0 / USB 3.0
- [x] 有线网卡（Intel ETH OK）
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

## Screenshots
![image1](https://github.com/teslia/hackintosh-clover-efi-for-asrock-z390-extreme4/blob/master/Screenshots/1.png?raw=true)
![image2](https://github.com/teslia/hackintosh-clover-efi-for-asrock-z390-extreme4/blob/master/Screenshots/2.png?raw=true)
![image3](https://github.com/teslia/hackintosh-clover-efi-for-asrock-z390-extreme4/blob/master/Screenshots/3.png?raw=true)
![image4](https://github.com/teslia/hackintosh-clover-efi-for-asrock-z390-extreme4/blob/master/Screenshots/4.png?raw=true)
