# Z390M-Gaming-X-Hackintosh-Opencore

Only for Opencore (Opencore 0.6.2)

![Screen Shot 2020-10-07 at 22 01 02](https://user-images.githubusercontent.com/71489512/95348840-a181b800-08e8-11eb-883f-e1be35d7e525.png)

# YOU MUST modify SN/UUID/MLB/ROM values in config.plist file and Use SMBIOS Imac 19.1

![Screen Shot 2020-10-07 at 22 05 44](https://user-images.githubusercontent.com/71489512/95349413-443a3680-08e9-11eb-9ef6-2de9c0cd3acd.png)

# Hardware
| Components  | Comments |     |
| ------------- | ------------- | ------------- |
| CPU  | Intel i5-9600K O.C to 4.9GHZ or 5.0GHZ | You can use another 8th/9th intel CPU |
| WiFi Adapter  | Boardcom 43602  | You can use another native boardcom card |
| Graphics Card  | AMD Radeon Vega 64 8GB | You can use another AMD graphics card |
| SSD  | WDC WDS100T2B0C  |
| RAM  | Corsair 32 GB 3000 MHZ  |
| Keyboard & Mouse  |  Magic Keyboard & Magic Mouse 2 & Magic Trackpad 2 |

# Bios
F9g version:
_Tweaker: +VT-d → Disabled
          +Intel(R) Speed Shift Technology → Enabled
          +Energy Efficient Turbo → Enabled
          +Intel(R) Turbo Boost Technology → Enabled
          +C-States Control:
            +CPU Enhanced Halt(C1E) → Enabled
            +C3 State Support → Enabled
            +C6/C7 State Support → Enabled
            +C8 State Support → Enabled
            +C10 State Support → Enabled
            +Package C State limit → Auto
_Extreme Memory Profile(X.M.P.) → Profile 1
_Advanced Memory Settings:
            +Memory Boot Mode → Disable Fast Boot (must) 
            +Memory Enhancement Settings → Enhanced Performance
_Settings:
            +Platform Power:
              +Platform Power Management → Disabled
              +AC Back → Always OFF
              +Power Loading → Enabled
              +RC6(Render Standby) → Enabled
            +IO Ports:
              +Initial Display Output → PCIe 1 Slot
              +Internal Graphics → Enabled
              +DVMT Pre-Allocated → 64M
              +DVMT Total-Gfx Mem → MAX
              +Aperture Size → 256M
              +Audio Controller → Enabled
              +Above 4G Decoding → Enabled
              +USB Configuration:
                +XHCI Hand-off → Enabled
                +Legacy USB Support → Enabled
                +USB Mass Storage Driver Support → Enabled
                +Port 60/64 Emulation → Disabled
              +Network Stack Configuration:
                +Network Stack → Disabled
              
       




