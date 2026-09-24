# ROMs – TrimUI Brick Pro

Bộ ROM đã lọc sẵn cho **TrimUI Brick Pro**. Chép nguyên thư mục `Roms/` vào gốc thẻ nhớ (SD card) là dùng được.

## Cấu trúc thư mục

Mỗi hệ máy có một thư mục riêng trong `Roms/`. Đặt file đúng định dạng vào đúng thư mục thì máy mới nhận game.

| Thư mục | Hệ máy | Định dạng file |
| --- | --- | --- |
| `FC` | NES / Famicom | `.nes`, `.fds`, `.zip` |
| `SFC` | SNES / Super Famicom | `.sfc`, `.smc`, `.zip` |
| `GB` | Game Boy | `.gb`, `.zip` |
| `GBC` | Game Boy Color | `.gbc`, `.zip` |
| `GBA` | Game Boy Advance | `.gba`, `.zip` |
| `MD` | Mega Drive / Genesis | `.md`, `.bin`, `.gen`, `.smd`, `.zip` |
| `MS` | Sega Master System | `.sms`, `.zip` |
| `GG` | Sega Game Gear | `.gg`, `.zip` |
| `SS` | Sega Saturn | `.chd`, `.cue` + `.bin` |
| `DC` | Sega Dreamcast | `.chd`, `.cdi`, `.gdi` |
| `PCE` | PC Engine / TurboGrafx-16 | `.pce`, `.chd`, `.cue` + `.bin` |
| `PS` | PlayStation 1 | `.chd`, `.pbp`, `.cue` + `.bin` |
| `PSP` | PlayStation Portable | `.iso`, `.cso`, `.chd` |
| `N64` | Nintendo 64 | `.z64`, `.n64`, `.v64` |
| `NDS` | Nintendo DS | `.nds` |
| `NGP` | Neo Geo Pocket / Color | `.ngp`, `.ngc` |
| `WS` | WonderSwan / Color | `.ws`, `.wsc` |
| `LYNX` | Atari Lynx | `.lnx` |
| `ATARI2600` | Atari 2600 | `.a26`, `.bin` |
| `ATARI7800` | Atari 7800 | `.a78`, `.bin` |
| `GW` | Game & Watch | `.mgw` |
| `PICO8` | PICO-8 | `.p8`, `.png` (`.p8.png`) |
| `NEOGEO` | Neo Geo (MVS/AES) | `.zip` (tên chuẩn MAME, vd. `mslug.zip`) |
| `CPS1` | Capcom CPS-1 | `.zip` (vd. `ffight.zip`, `dino.zip`) |
| `CPS2` | Capcom CPS-2 | `.zip` (vd. `ddsom.zip`, `avsp.zip`) |
| `CPS3` | Capcom CPS-3 | `.zip` (vd. `sfiii3.zip`) |
| `PGM` | IGS PolyGame Master | `.zip` |
| `FBNEO` | Arcade (FinalBurn Neo) | `.zip` |
| `MAME` | Arcade (MAME) | `.zip` |
| `MAME2003PLUS` | Arcade (MAME 2003-Plus) | `.zip` |
| `MAME2010` | Arcade (MAME 2010) | `.zip` |
| `ARCADE` | Arcade chung | `.zip` |
| `OPENBOR` | OpenBOR (beat 'em up) | `.pak` |
| `EASYRPG` | RPG Maker 2000/2003 | thư mục game / `.zip` |
| `FFMPEG` | Video | `.mp4`, `.mkv`, `.avi` |

## Lưu ý

- **Game arcade (`NEOGEO`, `CPS1/2/3`, `PGM`, `FBNEO`, `MAME*`) không được đổi tên file.** Máy nhận game theo tên zip chuẩn (vd. `mslug.zip`, **không** phải `Metal Slug.zip`) và **không giải nén** file zip.
- ROM set arcade phải khớp phiên bản emulator (FBNeo, MAME 2003-Plus, MAME 2010...). Dùng ClrMamePro hoặc RomVault với file DAT tương ứng để kiểm tra.
- **Neo Geo cần BIOS `neogeo.zip`**; PS1, Sega CD, Saturn, Dreamcast, FDS, GBA (tuỳ chọn) cũng cần BIOS. Đặt BIOS vào thư mục `Bios/` trên thẻ nhớ theo hướng dẫn của firmware.
- Game nhiều đĩa (PS1): nên chuyển sang `.chd` hoặc dùng file `.m3u` để gộp các đĩa.
- Các file `.gitkeep` chỉ dùng để giữ thư mục rỗng trong Git, có thể xoá hoặc để nguyên.
