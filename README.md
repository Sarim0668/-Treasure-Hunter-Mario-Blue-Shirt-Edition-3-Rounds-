# -Treasure-Hunter-Mario-Blue-Shirt-Edition-3-Rounds-
A complete x86 assembly console platformer featuring 3 levels × 3 scenes each with classic Mario mechanics! Control blue-shirt Mario as he collects coins, stomps enemies, uses power-ups, and battles bosses. Fully playable with high scores, timers, and smooth physics.  Made with pure x86 assembly + Irvine32 library – 8,000+ lines of optimized code!

🎮 Core Gameplay
Controls:
A/D → Move Left/Right
W → Jump (hold for higher)
SPACE → Shoot (when BIG!)
P → Pause
X → Exit
Objective: Complete 3 scenes per level (9 total scenes) by reaching the right side. Collect coins, avoid pits, stomp enemies!

HUD Features:
SCORE: 000000 | COINS: 00 | LIVES: 03 | WORLD 1-1 | TIME: 600 | MAGNET: OFF | POWER: OFF

✨ Main Features
📦 Collectibles & Power-Ups
Coins (C): +300 points each with musical sound!
Question Blocks (?): Hit from below → Coin or power-up
Coin Magnet (@): Pulls coins to you (8 seconds)
Growth Mushroom: Go BIG + shoot bullets (400 frames)


👹 Enemies & Combat
Goombas (G): Stomp to kill
Koopas (K): Stomp → Shell → KICK to kill multiple enemies!
Shell Physics: Kick left/right, bounces off walls, kills enemies


🌍 Levels & Hazards

Level 1: Classic Mario        → Pipes, platforms, obstacles
Level 2: Advanced             → Moving platforms, more enemies
Level 3: Boss Fight           → Giant turtle boss with fireballs
Pits: Fall → lose life

Pipes: Jump over green pipes (||)
Moving Platforms: Ride the wave
Breakable Walls: Hit from side/bottom


👑 Boss Battle (Level 3-3)
Giant turtle walks, shoots fireballs, jumps
Trigger fall → defeat with stomps
1000 points victory!


⏱️ Game Flow

Scene 1 → Scene 2 → Scene 3 → Level Complete!
3 Levels → Victory Screen → High Scores
Timer runs out → Game Over
0 Lives → Game Over

🏆 High Scores
Saved to highscores.txt
Top 10 players with names & scores
Enter name at start → compete with yourself!


🎵 Sound System
Instant sound effects :

Jump:    🎵 High beep
Coin:    🎵 Musical chime  
Power-up:🎵 Mid-high beep
Enemy:   🎵 Mid beep
Death:   🎵 Low beep
Shell:   🎵 Defeat sound
Boss:    🎵 Dramatic hit
Background: Looping WAV music

🛠️ Technical Features
✅ 8,000+ lines x86 assembly
✅ Smooth 60 FPS physics (gravity, acceleration)
✅ Double buffering (no flicker)
✅ Collision detection (player, bullets, shells)
✅ 3D positional audio effects
✅ File I/O for high scores
✅ Dynamic memory management
✅ Modular scene transitions
✅ Invincibility frames
✅ Bullet cooldown system


📁 Files
📄 SuperMario_COMPLETE_WITH_SHELLS.asm → Main game (165 KB)
📄 highscores.txt → Your scores
📁 sounds/ → Background music
📄 README.md → This file


🏅 Compile & Run
1. Install MASM32 or Visual Studio with MASM
2. Link Irvine32.lib (included macros)
3. ml /c /coff /Zi SuperMario_COMPLETE_WITH_SHELLS.asm
4. link SuperMario_COMPLETE_WITH_SHELLS.obj Irvine32.lib kernel32.lib user32.lib
5. Run COALPROJECT2.exe


🎯 Game Flow Demo
[Title Screen] → Enter Name → Level 1-1
→ Collect coins → Stomp Goombas → Level 1-2
→ Moving platforms → Level 1-3 → Level Complete!
→ Level 2 → Level 3 → BOSS FIGHT → VICTORY!
→ High Scores → Play Again?

🏆 Special Features
🔥 300pt coins (Treasure Hunter!)
🔥 Coin magnet auto-collects
🔥 Blue shirt Mario (custom skin)
🔥 Musical coin collection
🔥 Shell chaining (kick → kill → chain!)
🔥 Boss falling animation
🔥 3 full levels (9 scenes)


📈 Score System
Coin:           +300 pts
Stomp Goomba:   +100 pts  
Stomp Koopa:    +200 pts
Magnet:         +500 pts
Power-up:       +1000 pts
Boss Kill:      +1000 pts
Level Complete: +5000 pts


🎨 Visual Style
🟦 Blue Shirt Mario    → Player
🟡 Coins              → Collect
🟢 Pipes ||           → Hazards
🟤 Platforms          → Jump on
🟠 Enemies G/K        → Stomp
🟩 Shell o            → Kick!
🟪 Boss               → Fight


⭐ Star this repo! Fork and improve!
Made with ❤️ in x86 Assembly by Muhammad Sarim (24I-0668)

[1] Start Game     [2] Instructions
[3] High Scores    [4] Exit
Download & Play Now!

🎮 Treasure Hunter Mario – Blue Shirt Edition
     Muhammad Sarim | 24I-0668 | CS-A
