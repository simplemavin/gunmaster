# Gun Master

A weapon proficiency system mod. Gain experience by using your weapons and level up to strengthen them!

## 🎯 Mod Concept

**Gun Master** is a gameplay mod that provides a proficiency system for all guns. Gain experience by using your weapons, and each time you level up, a random weapon stat increases. The more you use your weapons, the stronger they become!

## ✨ Key Features

### 1. Weapon Support

The proficiency system applies to the following weapon types:
- Pistols, Submachine Guns, Assault Rifles, Battle Rifles
- Sniper Rifles, Shotguns, Magnums, Energy Guns, Bows

### 2. Experience Gain Methods

You can gain experience in the following ways by using your weapons:
Experience gained varies by weapon type.

### Headshot Hits
- Hitting an enemy's head immediately grants experience

### Enemy Kills
- Killing an enemy grants experience

### Headshot Kill Bonus
- Killing an enemy with a headshot grants additional bonus experience

### 3. Proficiency Level-Up System

- **Level Up**: Gain experience to increase your level
- **Stat Boost**: Each time you level up, one of the weapon's stats randomly increases (Very low chance to enhance multiple stats.)
- **Level Range**: Generally supports levels up to 100, with leveling beyond 100 also possible
- **Experience Requirements**: The experience required for the next level increases as your level gets higher, and significantly increases after level 100

### 4. Stat Boost System

Each time you level up, one of the 15 stats displayed on the weapon randomly increases.

### 5. Melee Weapon Proficiency System

The proficiency system also applies to melee weapons. Melee weapons have a different experience gain method compared to firearms:

#### Experience Gain Methods
- **Normal Attacks**
- **Enemy Kills**

#### Stat Boost
- Each time you level up, one of the 7 melee weapon-exclusive stats randomly increases.

### 6. Stat Point Mode
- An option to directly invest points gained from leveling up into desired stats.
- **Point Acquisition Rules**: Gain 1 point per level up, plus 2 additional points every 10 levels (10, 20, 30...)
- **Mode Switching**: You can switch between auto enhancement mode and manual distribution mode at any time in the settings window.
- **Investment Cost**: The first investment costs 1 point, and each subsequent investment in the same stat requires 1 more point (1, 2, 3, 4...).
- **Enhancement Amount**: Enhancement amount gradually increases with each investment, and a random range is applied to each investment.
  - Generally provides higher enhancement amounts than random enhancement when focusing on a single stat.
- **Reset Function**: You can reset invested points. Reset cost varies by level and consumes in-game money.
- **UI Access**: Right-click an item in the inventory to open the menu, then click the "Proficiency" button to open the stat point distribution window.

### 7. Settings Options
- **Settings Access Location**: You can access settings by opening the settings window in base map (base) or combat map.
- **Auto Distribution Mode Enable/Disable**: Switch between auto enhancement mode and manual distribution mode.
- **Enhancement Multiplier**: Set the multiplier applied to stat enhancements. (0.1x~3.0x)
  - Applies to both auto enhancement mode and manual distribution mode.
- **Experience Gain Multiplier**: Set the multiplier applied to experience gain. (0.1x~3.0x)
- **Experience Icon Display**: Display the icon of the currently equipped weapon next to the health bar and visually see the experience fill up. (Disabled/Enabled (Right-Left))
- **Backup File List**: View the list of saved backup files. The most recent backup file is selected by default.
- **Backup File Save and Load**: Save current state or select one of the saved backup files to restore data. Backup files are saved with timestamped filenames and up to 10 files are maintained.
- Files exceeding the count are removed, so if you want to keep a backup file, rename the backup file at C:\Users\{username}\AppData\LocalLow\TeamSoda\Duckov\GunMaster\proficiency_data_slot{slotNumber}.dat path (Steam) to proficiency_data_slot{slotNumber}_maintenance.dat and it will not be removed and will always be available in the backup file list.


## ⚠️ Warnings

- **Mod Deactivation Warning**: If you deactivate the mod and then reactivate it, the proficiency values assigned to your weapons may be reset.
- **Unexpected Shutdown Warning**: If an unexpected shutdown occurs, proficiency values may be reset or rolled back.
- **Data Backup Function Usage**: Since the mod's data is saved based on the latest version, using the data restore function may reset saved leveling.

## 📋 Patch Notes

### v1.2.8
- **Experience Icon Display Feature Added**
- Other balance adjustments

### v1.2.6
- **Movement Speed Stat Enhancement Feature Added**
- **Enhancement Logic Improvements**
- **Auto Distribution Mode Improvements**

## 📝 Notes

- All code and images were created with the help of AI
- If you have any bug reports or balance suggestions, please let us know

**Enjoy the game! 🎮**
