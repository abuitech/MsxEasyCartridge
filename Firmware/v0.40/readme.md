# Version 0.40

> **Warning**
> Before installing this version, please consider to backup roms files on the cartridge because the cartridge storage will be reformatted when the new firware is installed.

## Installation
After updating the Easy Cartridge firmware with **BasicRomEmulator_v0.40.uf2**, copying the folder **.sys** into Easy Cartridge at the root folder.

## Changes in this release

1. Add FM Panasoft Amusement Cartridge (SW-M004) / FM Music (Yamaha YM2413) emulation
    * YM2413 emulation with FM PAC 64Ko (Japanese and English) rom
    * YM2413 emulation with FM PAC 16Ko rom

2. Use lib SPIFTL (https://github.com/earlephilhower/SPIFTL) as FatFS implementation for built-in flash.

    > > *SPIFTL - Embedded, Static Wear-Leveling FTL Library*
    > > *(c) 2024 Earle F. Philhower, III earlephilhower@yahoo.com*

    > > *This library implements a static wear-leveling FTL algorithm suitable for use on embedded systems with SPI flash. Using static wear leveling should help extend the useful life of flash memory, especially when combined with the FAT filesystem which has certain high-write usage areas such as the FAT tables and directory entries.*

    > > *There were three design goals:*

    > > * *Preserve data*
    > > * *Keep the flash array within a limited PE (program/erase) cycle range*
    > > * *Miimize the memory at the cost of write speed*

