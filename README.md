# TRIXX Assets Repository

Official asset library for the **TRIXX GTA V Enhanced Mod Menu**.

---

## 📂 Installation & Where to Place These Files

All assets must be placed inside your Windows **Documents** folder under the `TRIXX\Assets` directory.

### Quick Path:
```text
C:\Users\<YourUsername>\Documents\TRIXX\Assets\
```
*(Or paste `%USERPROFILE%\Documents\TRIXX\Assets` into Windows File Explorer address bar)*

---

## 🛠️ Step-by-Step Setup

1. **Download or Clone this repository**:
   ```bash
   git clone https://github.com/asesatsawa/Assets.git "%USERPROFILE%\Documents\TRIXX\Assets"
   ```
   *Or download as ZIP from GitHub and extract the folder contents directly into `Documents\TRIXX\Assets\`.*

2. **Verify Folder Hierarchy**:
   Your folder structure should look like this:
   ```text
   Documents/
   └── TRIXX/
       ├── Assets/
       │   ├── branding/
       │   ├── fonts/
       │   ├── icons/
       │   ├── themes/
       │   ├── vehicle-previews/
       │   ├── INI Vehicles/
       │   ├── JSON Maps/
       │   ├── JSON Outfits/
       │   ├── JSON Vehicles/
       │   ├── SpoonerAssets/
       │   ├── XML Maps/
       │   ├── XML Outfits/
       │   ├── XML Vehicles/
       │   ├── Inter.ttf
       │   └── README.md
       └── DLCs/
           └── Vehicles/
               └── benze55/
                   └── dlc.rpf
   ```

---

## 🎮 In-Game Menu Mapping

| Folder | Menu Location | Notes |
| :--- | :--- | :--- |
| `JSON Maps/` | **Spawner / World ➔ JSON Maps** | Custom constructs & stunt tracks (Includes **Inverted Los Santos City**). |
| `XML Maps/` | **Spawner / World ➔ XML Maps** | Classic Menyoo & Spooner XML maps. |
| `JSON Vehicles/` | **Vehicles ➔ Saved / JSON Vehicles** | Custom tuned vehicle loadouts. |
| `XML Vehicles/` | **Vehicles ➔ XML Vehicles** | Menyoo XML custom vehicles. |
| `INI Vehicles/` | **Vehicles ➔ INI Vehicles** | Classic Menyoo/Trainer INI vehicle builds. |
| `JSON Outfits/` | **Player / Wardrobe ➔ JSON Outfits** | Custom player outfits & components. |
| `XML Outfits/` | **Player / Wardrobe ➔ XML Outfits** | Menyoo format saved outfits. |
| `vehicle-previews/` | **Vehicle Spawner** | Vehicle card thumbnails displayed on hover. |
| `fonts/`, `Inter.ttf` | **Menu Core** | UI typography and font engine. |
| `themes/`, `branding/` | **Settings ➔ UI Themes** | Custom menu themes, accents, and branding. |

---

## 🚗 Custom DLC Vehicle Packs (Add-Ons)

For standalone add-on car packs (`.rpf`), place them in:
```text
Documents\TRIXX\DLCs\Vehicles\<pack_name>\dlc.rpf
```
- **Example**: `Documents\TRIXX\DLCs\Vehicles\benze55\dlc.rpf`
- TRIXX mounts the archive in-memory via RAGE VFS and registers the model in GTA streaming tables automatically without editing `dlclist.xml` or modifying game files.
