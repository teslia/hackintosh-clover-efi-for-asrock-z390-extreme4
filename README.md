# hackintosh-clover-efi-for-asrock-z390-extreme4
华擎Z390 极限玩家4 黑苹果EFI文件    
Asrock Z390 Extreme4 Clover EFI files    
BIOS Version: 4.30     

## OpenCore Version (OC版本)
推荐使用OC版本！   
OC version is recommended!   
https://github.com/teslia/hackintosh-opencore-efi-for-asrock-z390-extreme4

## 已测试OSX版本 OSX Tested   
##### Catalina    

10.15.4  
10.15.3   
10.15.2   
10.15.1   
10.15   

##### Mojave      
*分支未测试，如果有问题请使用10.14分支！*     
*The master branch is NOT Tested，Please use `10.14` branch if not work.*      
    
10.14.6     
10.14.5    

## 重要说明！ Attention!
请使用[Clover Configurator](https://github.com/teslia/hackintosh-clover-efi-for-asrock-z390-extreme4/tree/master/Tools)修改config.plist中的序列号！     
You must use [Clover Configurator](https://github.com/teslia/hackintosh-clover-efi-for-asrock-z390-extreme4/tree/master/Tools) to modify the serial number in config. plist!
    
修改方法请参考[这里](https://github.com/teslia/hackintosh-clover-efi-for-asrock-z390-extreme4/tree/master/Change%20SN)    
Steps is [here](https://github.com/teslia/hackintosh-clover-efi-for-asrock-z390-extreme4/tree/master/Change%20SN)    

## 已测试项目
- [x] CPU变频
- [x] 显卡硬件加速(QE/CI)（Intel UHD Graphics 630 OK）
- [x] 板载ALC1220 音频输出  （ALC1220 Soundcard OK）
- [x] DisplayPort 视频/音频输出 （DP OK）
- [x] USB 2.0 / USB 3.0
- [x] 有线网卡（Intel ETH OK）
- [x] 睡眠和唤醒
- [x] NVRAM模拟 (use Clover rcScript)
   
## 无法使用(Failed feature)
- [ ] HDMI   

## NVRAM
由于Z390无法支持原生NVRAM，需要使用模拟NVRAM，将NVRAM/rcScript中的目录放入指定的位置重启即可支持。   
etc目录中的所有文件放入/etc   
Library目录中所有文件放入/Library   

## 我的配置 My hardware infomation
- Intel Core i9 9900K
- Lexar SSD 480G NVM.e
- DDR4 2666 8G x4 
- VP2780 4K Display use DisplayPort

## BIOS Settings:	
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
