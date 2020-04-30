> # Slackware, a retro? I don't think so!

## Slackware and RetroGaming
Collection of Packages for Slackware-stable
* Builded from sources on `slackware64-14.2`
* Packages contained SlackBuilds in `usr/doc/$PRGNAM-$VERSION/`
* Link to [Wiki](https://github.com/slacknk/slackretro/wiki) (russian language)

## Recommend 
Console |Libretro |Other Emulators
:---:         |:---:                                                                |:---: 
**Arcade**    |[fbneo](https://github.com/libretro/FBNeo)                           |[mame](https://www.mamedev.org/)_0.185
**DOS**       |                                                                     |[ScummVM](https://www.scummvm.org/), [DOSBox](https://www.dosbox.com/)
**GB/GBC/GBA**|                                                                     |[vba](https://sourceforge.net/projects/vbam/files/)-gtk2, [mgba](https://mgba.io/)-qt5
**NES**       |[fceu-mm](https://github.com/libretro/libretro-fceumm)               |[puNES](http://forums.nesdev.com/viewtopic.php?f=3&t=6928)
**SMD/MS/GG** |[genesis-plus-gx](https://docs.libretro.com/library/genesis_plus_gx/)|[Kega-Fusion](https://www.carpeludum.com/kega-fusion/) (!lib32)
**SNES**      |[snes9x2005-catsfc](https://docs.libretro.com/library/snes9x_2005/)  |[snes9x](https://github.com/snes9xgit/snes9x)-gtk2
**PCE**       |[pcefast-supergrafx](https://github.com/libretro/beetle-supergrafx-libretro)|[Hu-Go!](https://www.zeograd.com/parse.php?src=hugof&path=0,1,) (!lib32)
**PS1**       |[pcsx-rearmed](https://docs.libretro.com/library/pcsx_rearmed/)      |[ePSXe-Win](https://www.epsxe.com/) (!WINE)

* Gamepad-tool: [antimicro](https://github.com/AntiMicro/antimicro)
* Graphical Front-End: [RetroArch](https://www.retroarch.com/), [EmulationStation](https://emulationstation.org/), [Mednaffe](https://github.com/AmatCoder/mednaffe)


## Libretro-notes
#### NES
`Digital Devil Monogatari - Megami Tensei (J) [T+Eng1.00 SGST&Stardust&Tom (24.01.2018)]`
* Не запускается данный пропатченный ROM в `quicknes_20190914.cd302d9.451` и `nestopia-ue_20191127.3aab0a3.9`,
* через `fceu-mm_20191211.58030a3.785` и `mesen_20180802.1a7f07cf.2261` - игра запускается
#### SNES
`Tales of Phantasia (J) [T+Eng1.2_LowCase DeJap (12.02.2001)]`
  * `snes9x2005-plus` - замечено расхождение во звуке и некорректности графики
  * через `snes9x2005_git20190914.e5cadd2.655` - все нормально
