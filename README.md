# Keystroke-Combat
Keystroke Combat is A MIPS assembly shooting game developed using MARS during Spring 2024 for a final project.


# How to setup the game
After Opening [MARS](https://courses.missouristate.edu/kenvollmar/mars/index.htm) and opening the file `main.asm`:
- Open the 'Bitmap Display' (Tools>Bitmap-Display)
- set Display Height in Pixels: 512
- Resized your Bitmap Display Window
- Click On 'Connect To MIPS'
- Open the 'Keyboard and Display MMIO Simulator' (Tools>Keyboard-and-Display-MMIO-Simulator)
- Click On 'Connect To MIPS'

From there, everything should be ready, press CapsLock, compile, run and enjoy!

[![IMAGE ALT](https://img.youtube.com/vi/5jMjjL_Z0Ec/0.jpg)](https://www.youtube.com/watch?v=5jMjjL_Z0Ec)

# Game explanation: 
Keystroke Combat is a multiplayer game where each player using a different set of keyboard 
controls must try their best to eliminate their opponent while defending themselves. Player 1 
would use “WASD” while Player 2 would use “IJKL” and each of them will have to type-in 
combos to either attack their opponent by shooting a bullet, or combos to shield themselves 
against attacks. The combos will of course be displayed on screen and the player will have 
many attacks and defenses to choose from (Level 1 and level 2 Bullet/ Level 1 and level 2 
Shield). You must be wary though as you load in a combo, as your opponent can see your 
loading progress in the lower part of the screen and might decide to retaliate, or initiate defense. 
This is indeed a game of speed and reflexes and the first player to drain their opponent’s entire 
health (displayed above) wins. As for the HP draining itself, that will be based on the type of 
attacks and defenses. If a player has no shield, the full damage will be taken, but of course if a 
player does indeed have a shield, only a portion of the damage will be taken (If any at all), the 
damage is then equal to the difference between the bullet level and the shield level. Note that 
every level of bullet has its own combo, as well as every level of shield. This is indeed a very 
fast-paced game. But that’s enough yapping, pull out your keyboards and type out some bullets.
