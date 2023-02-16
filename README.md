# npdrm_free_mod
by qwikrazor87, modified by lusid1

A PSP/ePSP plugin to run official NPDRM PS1/PSP content without need of a valid .rif license or act.dat.

## Usage
- Place npdrm_free_mod.prx at ms0:/seplugins/npdrm_free_mod.prx.
- Enable plugin in both ms0:/seplugins/game.txt and ms0:/seplugins/vsh.txt.
- Write this line in both .txt files:
	ms0:/seplugins/npdrm_free_mod.prx 1
- Restart VSH, now you can run any official PSN content without a license.

ALL content MUST be encrypted and left as is from official .pkg for this plugin to work, otherwise use NoDRM engine in PRO CFW.

NOTE: This modified version will not load DLC on its own.  It is intended to be used in conjuction with nploader_mod which now supports both encrypted and decrypted DLC.

## Changelog
### v7.3 (MOD)
- Disabled loading of encrypted DLC to avoid crashing when used with nploader_mod
### v7.2
- Suspend/resume issue should be fixed, thanks to kyleatlast.
### v7.1
- Fixed the import scanning function that caused a crash on false positives.
### v7.0
- This plugin now patches the core of npdrm to decrypt content if and only if the official method (rif + act.dat) fails
- Now you can run official PSN games and DLC without needing to decrypt them.
- Now generates KEYS.BIN for official PSN PS1 EBOOTs on-the-fly if needed.
- PSN TG-16/PC Engine games can now be run without first decrypting any content, do NOT decrypt the PSP-KEY.EDAT for it.
- PTF themes requiring a license can now be installed.
- Suspend issue from previous versions should now be fixed, if not try disabling all other plugins.

## Credits
Huge thanks to all involved in the PSP/ePSP/PSVita homebrew community, devs and users alike,
without whom I would not be able to accomplish this task. You are too numerous to name.

Big thanks to kyleatlast who revived this project by finally fixing the suspend issue in ePSP.

## Author's notes
Contact me for issues if needed.
- @qwikrazor87 on Twitter (http://twitter.com/qwikrazor87)
- qwikrazor87 on Wololo Forum (http://wololo.net/talk)
- qwikrazor87 on github (https://github.com/qwikrazor87)

I hope you enjoy this plugin as much as I did making it and figuring out how PSP NPDRM works. :)


