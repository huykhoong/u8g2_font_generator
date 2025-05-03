# u8g2 Font Generator (Windows EXE)

**Version:** 1.0.0  
**Author:** Huykhong  
**Copyright:** © 2025 Huykhong  

---

## ◦ Overview  
A standalone Windows EXE tool that converts directly TrueType fonts (TTF) into C header files (.h) compatible with u8g2/LovyanGFX. Suppport Vietnamese and other non-asCII language.

## ◦ Key Features  
• Select your TTF file, font size, and character mapping range.  
• Automatic cleanup of the BDF file after header generation.  
• Simple GUI designed for embedded C/C++ projects.  

## ◦ Usage  
1. Download `u8g2_font_generator.exe` from the Releases page.  
2. Launch the EXE—the interface will appear:  
 • Click **Browser** to choose a `.ttf` font.  
 • Enter **Size** (default is 12).  
 • Enter **Mapping** (e.g. `32-126,160-255,…`) or pick a preset.  
 • Click **Save as** to specify where to save the `.h` file.  
 • Click **Export .h** (Generate Font) and wait for completion.  
3. Your C header file `.h` will be created at the chosen location.
4. `#include "yourfont.h"` then `u8g2.setFont(yourfont)` to use.

## ◦ System Requirements  
• Windows 7 or later (32/64-bit)    

## ◦ Closed-Source Distribution  
> **NOTICE:** This tool is distributed as **closed-source**.  
> Only the compiled `.exe` is shared. The original source code is not included.  

## ◦ Support & Contact  
If you encounter any issues or have questions, please reach out:  
– Facebook: https://fb.me/huykhoong
– Website: https://huykhong.com  
