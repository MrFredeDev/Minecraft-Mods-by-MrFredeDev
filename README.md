## Installing the mod in Minecraft 26.1

### Step 1 — Install Java 25
Download from: **https://adoptium.net**
Choose: **Temurin 25** → your operating system → JRE package → Install

### Step 2 — Install NeoForge
1. Go to **https://neoforged.net** and download the installer for **Minecraft 26.1**
2. Double-click the downloaded `.jar` file (Java must be installed first)
3. Select **Install client** and click OK
4. NeoForge will create a new profile in the Minecraft Launcher automatically

### Step 3 — Add the mod
Copy `advancedmining-2.0.0.jar` into your mods folder:
- **Windows:** Press Win+R, type `%appdata%\.minecraft\mods`, press Enter
- **macOS:** Go to `~/Library/Application Support/minecraft/mods`
- **Linux:** `~/.minecraft/mods`

If the `mods` folder doesn't exist, create it.

### Step 4 — Launch Minecraft
1. Open the Minecraft Launcher
2. In the bottom-left, switch the profile to **NeoForge 26.1**
3. Click **Play**

---

## Using the enchantments

Apply via enchanting table or anvil, or in creative mode:
```
/enchant @s advancedmining:excavator  7
/enchant @s advancedmining:vein_miner 3
/enchant @s minecraft:efficiency      8
/enchant @s minecraft:sharpness       8
```

## Enchantment tiers

| Enchantment | Max Level | Effect |
|---|---|---|
| Excavator I–III | 3×3 face | 1–3 blocks deep |
| Excavator IV–VII | 4×4 face | 1–4 blocks deep |
| Vein Miner I | up to 64 ores | BFS whole-vein harvest |
| Vein Miner II | up to 128 ores | |
| Vein Miner III | up to 256 ores | |
