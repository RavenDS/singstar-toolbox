# Singstar PS2 Toolbox
A Custom Disc Creator for Singstar PS2. 

## Setup
##### Download the latest version of ffmpeg.exe <a href="https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z">(direct link for Win10)</a> and place it in the same folder as Singstar Toolbox.
##### After the initial setup, do NOT move or edit any files in /tools/ folder, as this may lead to data corruption.

## Features
- Re-encode all .txt with UTF-8 & fix line breaks
- Audio normalization for consistent volume
- Create Medleys automatically
- Pack & Unpack Singstar .PAK files
- ISO is compatible with emulators & hardware *(tested on PCSX2 and PS3)*

## To-Do
*The current limitations and to-do list will evolve as the tool is being worked on.*

- Reverse-engineer newer Singstar versions for Rap support
- Entirely rewrite the TXT2XML converter to accomodate for Rap notes and multiple singers *(Duet)*
- Multiple language support (currently only English)
- Rewrite the BMP to TX2 algorithm for better image quality
- Improve the audio conversion algorithm to get rid of MFAudio
- Let user customize Intros, Logos, Menu Music..

## Credits
*Singstar Toolbox is partially based on the ancient Singstar Creator V3, which included several tools whose authors were not named.*

- ffmpeg team for <a href="https://ffmpeg.org/">ffmpeg</a>
- Raynê Games for <a href="https://residentevilmodding.boards.net/thread/17381/tool-dump-rebuild-ps2-iso">PS2 ISO Rebuilder</a>
- Nethunter/Fulgore & Co. for BMP2TX2
- Holger Kuhn (hawkear@gmx.de) for SDK2SS
