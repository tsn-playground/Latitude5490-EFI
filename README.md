# macOS Ventura and Sequoia for Dell Latitude 5490 (MacBookPro15,2)

A fully working EFI, made by @JhonatanRian

Note: Use HeliPort if you want to use Sonoma / Sequoia

## Thanks to those who helped me with this EFI:
  - [@TECHNIKVERBOT](https://github.com/TECHNIKVERBOT) for the re-work and Sequoia patches.
  - [@C1014](https://github.com/C1014) for helping me boot Ventura for the first time.

## Opencore
### Version tested:
  - 13.06: "Ventura"
  - 15.4: "Sequoia"

## Build Config.plist
 - [Link](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html)

## System information

### Configuration

| Specifications      | Details                                          |
| :---                |:---                                              |
| Computer model      | Dell Latitude 5490                               |
| Processor           | Intel Core i5-8350U Processor @ 1.8 GHz          |
| Memory              | 16 GB DDR4 2400 MHz                              |
| Hard Disk           | SSD 500gb                                        |
| Integrated Graphics | Intel(R) UHD Graphics 620                        |
| Screen              | Display @ 1920 x 1080 (13.9 inch)                |
| Sound Card          | Realtek ALC256                                   |
| Wireless Card       | Intel Dual Band Wireless-AC 8265/8275            |
| Bluetooth Card      | Intel Bluetooth 8265/8275                        |

## What's working:
  - Touchpad                       ✅
  - Keyboard                       ✅
  - HDMI                           ✅
  - VGA                            ✅
  - USB Ports                      ✅
  - Sleep                          ✅
  - Battery percentage             ✅
  - Microphone                     ✅
  - Headphone jack                 ✅
  - Wi-Fi with itlwm               ✅
  - Ethernet                       ✅
  - Webcam                         ✅
  - USB-C                          ✅
  - Hardware acceleration          ✅

## What's not tested:
  - SD Card Reader

## Bugs (only on Sequoia):
  - Intel Bluetooth (needs patches)
  - AirPortitlwm (only works on Ventura)
  - Brightness slider (-igfxblt and -igfxbls won't work)

## Screenshots
![](https://github.com/JhonatanRian/EFI_DELL_LATITUDE_5490/blob/main/screenshots/iScreen%20Shoter%20-%20Terminal%20-%20240130234633.png?raw=true)

![](https://github.com/JhonatanRian/EFI_DELL_LATITUDE_5490/blob/main/screenshots/iScreen%20Shoter%20-%20Monitor%20de%20Atividade%20-%20240130235025.png?raw=true)
