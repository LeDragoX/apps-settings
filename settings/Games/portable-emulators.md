# Portable Emulators

_A comprehensive guide to getting some emulators in portable mode._

## 🪟 Windows

- I-mode:
  - KeitaiWorldLauncher - **Already portable**.
- Nintendo 3DS:
  - Azahar/Citra - Create "user" folder.
- Nintendo DS:
  - MelonDS - Create "**bios**", "**cheats**", "**saves**", "**savestates**" and "**sdcard**" folders
  - In **Config > Emu settings**, set "**DS-Mode**" and "**DSi-Mode**" files to "**bios/{FILENAME}.bin**"
  - In **Config > Path settings** put: - Saves files path: "**saves**" - Savestates files path: "**savestates**" - Cheats files path: "**cheats**"

> [!NOTE]
> Using "portable" folder isn't working, gives `read/write` errors.

- Nintendo GameCube/Wii:
  - **Dolphin** - Create "User" folder;
- Nintendo Switch:
  - **Citron/Yuzu** - Create "user" folder;
  - **Ryubing/Ryujinx** - Create "portable" folder;
- Nintendo Wii U:
  - **Cemu** - Create "portable" folder;
- PlayStation 1:
  - **Duckstation** - Create "portable.txt" file;
- PlayStation 2:
  - **PCSX2** - Create "portable.txt" file, try creating "portable;ini" otherwise;
- PlayStation 3:
  - **RPCS3** - **Already portable**;
- PlayStation 4:
  - **shadPS4** - Create "launcher" and "user" folder;
- PlayStation Portable:
  - **PPSSPP** - **Already portable**;
- PlayStation Vita:
  - **Vita3K** - Create "portable" folder;
- Xbox:
  - **Xemu** - Create "xemu.toml" file and "bios", "boot", "hdd" folders;
  - Now, add these lines to "xemu.toml" file using a text editor of your choice, the file names may vary.

<details>
<summary>xemu.toml</summary>

```toml
[sys.files]
bootrom_path = 'boot\mcpx_1.0.bin'
flashrom_path = 'bios\bios4627dev.bin'
eeprom_path = 'bios\eeprom.bin'
hdd_path = 'hdd\xbox_hdd.qcow2'
```

</details>

- Xbox 360:
  - **Xenia** - Create "portable.txt" file;
- Retro Games (AIO)
  - **RetroArch** - **Already portable**.

> [!IMPORTANT]
> After getting all emulators to portable mode, press `Windows + R` and enter `%appdata%`, there should be your old settings folder which you can move to the portable folder.

## 🐧 Linux

In Linux, simply download the **.AppImage** version for:

- **Azahar** - Create "user" folder;
- **Cemu** - Create "portable" folder;
- **Citron** - Create "user" folder;
- **RPCS3** - Create "portable" folder;
- **shadPS4** - Create "user" folder;
- **Xenia Canary** - Create "portable.txt" file.

### Other Cases

In AppImage format, all settings relying on the file can be in portable mode, by creating a folder using the "**FILENAME.AppImage.config**" name format.

- **Duckstation** - `DuckStation-x64.AppImage` (file) > `DuckStation-x64.AppImage.config` (folder);
- **MelonDS** - `melonDS-x86_64.AppImage` > `melonDS-x86_64.AppImage.config`
- **PCSX2** - `pcsx2-x64.AppImage` > `pcsx2-x64.AppImage.config`
- **PPSSPP** - `PPSSPP-x86_64.AppImage` > `PPSSPP-x86_64.AppImage.config`
- **RetroArch** - `RetroArch-Linux-x86_64.AppImage` > `RetroArch-Linux-x86_64.AppImage.config`
- **Ryujinx** - `ryujinx-x64.AppImage` > `ryujinx-x64.AppImage.config`
- **Vita3K** - `Vita3K-x86_64.AppImage` > `Vita3K-x86_64.AppImage.home`
- **Xemu** - `xemu-x86_64.AppImage` > `xemu-x86_64.AppImage.home`
