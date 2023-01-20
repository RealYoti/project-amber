# project-amber
WebKit+Kernel exploit chain for all actual PS Vita firmwares
![Amber.png](Amber.png?raw=true "Amber.png")

## Installation
### PS Vita 1000/1100 with memory card or PS Vita 2000/TV
 1. Open HENlo host (e.g. http://vitawiki.xyz/henlo) in the Vita browser
 2. Install HENkaku -> Download VitaShell -> Reset taiHEN config.txt -> Exit
### PS Vita 1000/1100 without memory card (but with SD2VITA)
 1. Prepare SD2VITA on your PC
 2. Open HENlo host (e.g. http://vitawiki.xyz/henlo) in the Vita browser
 3. Install HENkaku -> Install SD2VITA as ux0 -> Exit
 4. Check your memory card in [Settings](https://manuals.playstation.net/document/en/psvita/settings/system.html)
 5. Reopen host with your real firmware (e.g. http://vitawiki.xyz/henlo?3.65)
 6. Download VitaShell -> Exit
#### Download VitaShell errors
 * 80010013 Memory card not detected, recheck your memory card in [Settings](https://manuals.playstation.net/document/en/psvita/settings/system.html)
 * 80af5025 Reboot -> open host -> Exit -> open host -> Download VitaShell
 * 80870005 Reboot -> open host -> Exit, run VitaShell from the Home screen

## Usage
 1. Open HENlo host (e.g. http://vitawiki.xyz/henlo) in the Vita browser
 2. Exit

## Credits
 * Mostly based on [HENlo](https://github.com/TheOfficialFloW/HENlo) by [TheFloW](https://github.com/TheOfficialFloW)
 * Some offsets from [henlo_jb](https://github.com/SKGleba/henlo_jb) by [SKGleba](https://github.com/SKGleba)
 * Amber logo by [Once](https://github.com/once13one) (thanks a lot!)
