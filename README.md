[README.md](https://github.com/user-attachments/files/28793630/README.md)
# Advanced Mining Suite — Minecraft 26.1 (NeoForge)

Three pickaxe enchantments: **Excavator** (VII tiers, up to 4×4×4 area mining),
**Vein Miner** (III tiers, full-ore-vein BFS harvesting), and
**Limit Breaker** (extends vanilla enchantment caps via anvil + JSON overrides).

---

## How to get the playable .jar file (no coding needed)

### Step 1 — Create a free GitHub account
Go to **https://github.com** and sign up. It's free.

### Step 2 — Create a new repository
1. Click the **+** button (top-right) → **New repository**
2. Name it `advancedmining` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload these files
1. On your new repo page click **uploading an existing file**
2. Drag and drop **every file and folder** from this zip into the upload window
   - Make sure the folder structure is preserved (src/, .github/, gradle/, etc.)
3. Click **Commit changes**

### Step 4 — Wait ~5 minutes for GitHub to compile it
1. Click the **Actions** tab on your repository page
2. You'll see a workflow called **"Build Advanced Mining Suite"** running
3. Wait for the green ✅ checkmark

### Step 5 — Download your compiled .jar
1. Click on the completed workflow run
2. Scroll to the bottom — you'll see **Artifacts**
3. Click **advancedmining-mod-jar** to download a zip
4. Unzip it — inside is `advancedmining-2.0.0.jar` — that's your mod file!

---

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
