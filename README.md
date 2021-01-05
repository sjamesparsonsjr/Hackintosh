

<p align="center">
<img src="/hackintosh.png.png" width="200">
</p>

# Hackintosh

*TL;DR* My journy on building a Hackintosh

I've always been a fan of Apple, however, it appears the power to cost ratio will be improved if I build this machine.  Also, the repairability and feasibility of logic level repairs are difficult and time-consuming. 

## Hardware

### Facebook Marketplace $200
|Hardware|Link  |Cost| Notes|
|--|--|--|--|
|Intel i7 4770k  | https://intel.ly/3bb0ekc  | $37.50|$75 on Ebay |
|Asus Sabertooth z87  | https://bit.ly/3pP4cD5 |$85.68 |$180 on Ebay|
| 16gb Corsair Vengeance LP Ram | https://bit.ly/35c6dRU | $33.32|$70 on Ebay |
| Corsair Water Cooling Pump and Radiator| |$45.22|$95 on Ebay| 
### Amazon
|Hardware|Link  |Cost| Notes|
|--|--|--|--|
|Fans |https://amzn.to/2LkDNhD |$15.00| |
|SATA Cable|https://amzn.to/389ZidV  |$7.00 | |
| Power Supply|https://amzn.to/38aYzZS|$64.99|  |
|1 TB SSD Harddrive|https://amzn.to/2JMCAzc|99.99||
|16gb Corsair Vengeance LP Ram|https://amzn.to/2XaMI80|$66.99||
|Wifi Card|https://amzn.to/38hvE6u|$49.99||

### InOs Local PC Repairshop
|Hardware|Link  |Cost| Notes|
|--|--|--|--|
|GAMDIAS Case||$45.00| 50% off for damage|

## Total $549
<span style="color:red">*$549*</span>.

## Support Websites
[Things to know](https://www.tonymacx86.com/threads/file-structure-some-of-the-things-i-wish-i-knew-before-starting.272699/)

[Sabertooth z87 guide](https://www.tonymacx86.com/threads/success-asus-sabertooth-z87-i7-4970k.227775/)

[Flash BIOS](https://www.youtube.com/watch?v=0Po88MpYhhw)
<a href="https://www.youtube.com/watch?v=0Po88MpYhhw" target="_blank">Flash BIOS</a>

[Sabertooth PDF](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjz--e8rYPuAhUBm1kKHRimDSAQFjAAegQIBRAC&url=https%3A%2F%2Fwww.pugetsystems.com%2Ffiles%2F3435%2Fparts%2FMotherboard%2FAsus-Sabertooth-Z87-9474%2FE7868_SAbertooth_Z87.pdf&usg=AOvVaw0q3tLwz9cgDImUOMhCfkg8)

## Steps
- [x] **Hardware**
1. Add power supply to case
2. Add fans to radiator
3. Add water cooler to case
4. Add mother board to case **NOTE** Install fans, water radiator, IO port cover first
5. Wire Managment
6. Add ram to motherboard
7. Add SATA cable
8. Add SSD to Harddrive

- [X] ~~Bios~~ UEFI (Unified Extensible Firmware Interface) 
9. Download BIOS driver [Guide](https://www.asus.com/support/FAQ/1038568/)
10.  Update BIOS driver
- [X] BIOS Settings
11. Legacy USB Support -> Auto **NOTE** Located in Advanced -> USB onfiguration
12. EHCI Hand-off -> Enabled **NOTE** Located in Advanced -> USB onfiguration
13. Intel xHCI Mode -> "Smart Auto" / "Enabled" both works **NOTE** Located in Advanced -> USB onfiguration
14. OS Type -> Other OS **NOTE** Located in Boot -> Secure Boot
15. Log into BIOS and select Clover Bot from EFI **NOTE** Seems the USB 2.0 port on the case wont work, but the 3.0 port on the case worked.


First run with Clover, loged into MacOS external. 





- [ ] Formate Harddrive
- [ ] Build Operating System



## Manual


## Authors

* **[S James Parsons Jr](https://www.linkedin.com/in/sjamesparsonsjr/)** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## AppStore
[Find the Completed App Here](https://apps.apple.com/us/app/qurrent/id1234567)





> Written with [StackEdit](https://stackedit.io/).
