![Platform](https://img.shields.io/badge/Platform-iOS-lightgrey.svg?style=flat)
![Platform](https://img.shields.io/badge/Platform-mac-lightgrey.svg?style=flat)
![License](https://img.shields.io/badge/Language-Objective--C-blue.svg)
![Level](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)

# TransNSString

translate/localize your strings in runtime (no more strings files for tranalate) with most language on your device tested on iOS device for Cydia Substrate tweaks, also could work on your iOS Application, for now doesn't work inside simulator but i THINK it should work on the real device

**Why i created it**

it helps u to protect some strings to be changed like your credits means ( to make it hard to change your credits information, you can use some obfuscate to make it harder also ;) )

**Usage**

<pre>
NSString *newString = [NSString translateToAR:@"تجربة" toCA:nil toCS:nil toDA:nil toDE:nil toEL:nil toEN:@"Test" toEN_AU:nil toEN_GB:@"EN_GB" toES:nil toES_MX:nil toFI:nil toFR:@"Essayer" toFR_CA:nil toHE:nil toHI:nil toHR:nil toHU:nil toID:nil toIT:nil toJA:nil toKO:nil toMS:nil toNL:nil toNO:nil toPL:nil toPT:nil toPT_PT:nil toRO:nil toRU:nil toSK:nil toSV:nil toTH:nil toTR:nil toUK:nil toVI:nil toZH_CN:nil toZH_HK:nil toZH_TW:nil];
</pre>

**To Do**

* add Google translator
* add Bing translator

**Credits**

TransNSString is brought to you by **Mokhlas Hussein** <a href="http://www.imokhles.com/">@iMokhles</a>