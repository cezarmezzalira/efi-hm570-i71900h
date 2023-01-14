# EFI-Hackintosh- HM570 Interposer - Intel Core i7 11900H

Sucessful Big Sur installation with 11th Generation CPU and B560M Aorus Elite motherboard

## Current System Info

- MacPro1,1
- MacOS Big Sur 11.7.2 (20G1020)

## Hardware

|       Type       | Item                                          |
| :--------------: | --------------------------------------------- |
|     **CPU**      | [ Intel Core i7 11900H ]                      |
| **Motherboard**  | [ HM570 Interposer ]                          |
|     **RAM**      | [ 2x16GB Patriot Viper 3200MHz ]              |
|     **GPU**      | [ Gigabyte GTX 760 Windforce 2 OC 2GB GDDR5 ] |
|     **SSD**      | [ Netac NV3000 NVME 1TB ]                     |
| **Power Supply** | [ OCZ ZT650W ]                                |
|     **Wifi**     | [ BCM94360CS2 Native with Bluetooth ]         |

## Not Working hardware

- Audio: AppleALC not working

## Working hardware

- Wifi: native
- GPU: native working until Big Sur
- USB: `USBMap.kext` with onboard only

## Important thing if you use this EFI:

Update **config.plist** in PlatformInfo > Generic with YOUR informations.
<br><br>
_1. MLB (Board Serial)
<br> 2. ROM (Mac Address)
<br> 3. SystemSerialNumber (Serial)
<br> 4. SystemUUID (SmUUID)_

Please use [_genSMBIOS_](https://github.com/corpnewt/GenSMBIOS/archive/refs/heads/master.zip) for generate values for above itens.
<br>
Please use [_ProperTree_](https://github.com/corpnewt/ProperTree/archive/refs/heads/master.zip) for configure/edit your config.plist.
