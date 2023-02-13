# C64 #

[![donate](https://img.shields.io/badge/donate-PayPal-blue.svg)](https://www.paypal.me/Sinclair81)

## TinyAdapter ##

<!-- markdownlint-disable MD033 -->
<img src="https://raw.githubusercontent.com/Sinclair81/C64/master/TinyAdapter/TinyAdapter.png" align="center" alt="TinyAdapter" height="249" width="472">
<!-- markdownlint-enable MD033 -->

### Adapterplatine für den Tiny-EPROMer ###

"Mit der kleinen, einfach nachzubauenden Zusatzplatine können Sie die Leistungsfähigkeit des Tiny-EPROMers
erheblich verbessern. So lassen sich mit ihr zusätzlich zu den EPROM-Typen 2764, 27128 und 27256 die Typen
27512 und 2732A proplemlos brennen und die im C64 eingebauten ROMs 2364 lesen."
64'er 12/1988 Seite 61

### Adapter board for the Tiny-EPROMer ###

"With the small, easy-to-rebuild additional circuit board, you can use the performance of the Tiny-EPROMer
improve significantly. In addition to the EPROM types 2764, 27128 and 27256, the types
Burn 27512 and 2732A without any problems and read the 2364 ROMs built into the C64."
64'er 12/1988 page 61


## Kernel adjustments ##

HEX address | description      | C64 Original                          | EXOS v3  
------------|------------------|---------------------------------------|--------  
0355        | font color       | 0E                                    | 0F  
0CD9        | edge color       | 0E                                    | 00  
0CDA        | background color | 06                                    | 00  
0460 - 0470 | Text 17 Byte     | " BASIC BYTES FREE"                   | " BASIC BYTES FREE"  
0475 - 0497 | Text 35 Byte     | "    **** COMMODORE 64 BASIC V2 ****" | "    *** C64 IMPROVED BY EXOS V3 ***"
049A - 04AA | Text 17 Byte     | " 64K RAM SYSTEM  "                   | "  BY J.SCHEMMEL  "

## Color palette ##

HEX | Color
----| -----
00  | black
01  | white
02  | red
03  | cyan
04  | violet
05  | green
06  | blue
07  | yellow
08  | orange
09  | brown
0A  | lightred
0B  | darkgrey
0C  | midgrey
0D  | lightgreen
0E  | lightblue
0F  | lightgrey
