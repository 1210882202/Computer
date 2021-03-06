# 我的电脑：
## 文件：
|名称|日期|
|:-|:-|
|EFI.zip|2022.07.05|

## 备注：
>Root
>>Booter
>>>Quirks
>>>>DevirtualiseMmio -> Yes  
>>>>EnableWriteUnprotector -> No  
>>>>ProtectUefiServices -> Yes  
>>>>RebuildAppleMemoryMap -> Yes  
>>>>ResizeAppleGpuBars -> -1  
>>>>SetupVirtualMap -> No  
>>>>SyncRuntimePermissions -> Yes

>>DeviceProperties
>>>Add
>>>>`添加`PciRoot(0x0)/Pci(0x2,0x0): Dictionary
>>>>>AAPL,ig-platform-id: Data: 0300C89B

>>>>PciRoot(0x0)/Pci(0x1b,0x0) -> PciRoot(0x0)/Pci(0x1f,0x3)
>>>>>layout-id -> 03000000

>>Kernel
>>>Quirks
>>>>AppleXcpmCfgLock -> Yes  
>>>>DisableIoMapper -> Yes  
>>>>PanicNoKextDump -> Yes  
>>>>PowerTimeoutKernelPanic -> Yes  
>>>>XhciPortLimit -> No

>>Misc
>>>Boot
>>>>HideAuxiliary -> Yes  
>>>>LauncherOption -> Full  
>>>>PickerMode -> External  
>>>>PickerVariant -> Acidanthera\MyImg  
>>>>Timeout -> 7

>>>Debug
>>>>AppleDebug -> No  
>>>>ApplePanic -> No  
>>>>DisableWatchDog -> Yes  
>>>>Target -> 3

>>Security
>>>AllowNvramReset -> Yes  
>>>AllowSetDefault -> Yes  
>>>BlacklistAppleUpdate -> Yes  
>>>AllowToggleSip -> Yes  
>>>ScanPolicy -> 0  
>>>SecureBootModel -> j185  
>>>Vault -> Optional

>>NVRAM
>>>Add
>>>>7C436110-AB2A-4BBB-A880-FE41995C9F82
>>>>>SystemAudioVolume -> 32  
>>>>>boot-args -> agdpmod=pikera  
>>>>>prev-lang:kbd -> 7A682D48 616E733A 323532

>>PlatformInfo
>>>Generic
>>>>MLB -> `Board Serial`  
>>>>ROM -> `Apple ROM`  
>>>>SystemProductName -> iMac20,1  
>>>>SystemSerialNumber -> `Serial`  
>>>>SystemUUID -> `SmUUID`

>>UEFI
>>>Audio
>>>>AudioDevice -> PciRoot(0x0)/Pci(0x1f,0x3)  
>>>>AudioSupport -> Yes  
>>>>PlayChime -> Enabled  

>>>Output
>>>>UIScale -> 2

## 硬件：
|部件|品牌型号|数量|单价|
|:-:|:-|:-:|:-|
|机箱|先马 米立方|1|￥189->179|
|电源|安钛克 NE850 金牌全模组|1|￥759->649|
|主板|技嘉 Z490M-GAMING-X|1|￥899|
|CPU|Intel 盒装i7-10700k|1|￥2289|
|散热|九州风神 阿萨辛3代|1|￥599->499|
|内存|美商海盗船 DDR4 3200 16G * 2|1|￥929.9|
|硬盘|西部数据 NVMe SN550 500G|1|￥389|
||西部数据 SATA3.0固态蓝盘 500G|1|￥479|
||西部数据 SATA机械蓝盘 2T|1|￥388|
|显卡|磐镭 AMD5500XT 8G|1|￥2478|
|无线网卡|博通 BCM94360CD精装|1|￥225|
|风扇|猫头鹰 NF-A12*25 PWM|1|￥289|
||猫头鹰 NF-A20 PWM|1|￥249|
|光驱|华硕 24倍速 SATA接口 内置DVD刻录|1|￥139->129|
|音箱|纽曼 BT55 白色|1|￥29.9|
|麦克风|索爱 SA-L28 经典款|1|￥23.9|
|摄像头|奥尼 640p不带麦克风|1|￥77.42|
|硅脂|利民 TF8 1.2g|1|￥29.9|
|ESATA挡板|微星|1|￥23|
|螺丝刀|澳胜 25件|1|￥29->22.5|
|DP线|绿联 1.4版8K 胶壳款 1m|1|￥59|
|网线|绿联 六类圆线 5m|1|￥21.9->18.9|
|u盘|金士顿 多彩时尚3.2 32G|2|￥24.8|
||铠侠 隼闪2.0 32G|1|￥23.9|