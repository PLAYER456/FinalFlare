# Final Flare
Game Development - Final Flare

Game Development - Multiplayer Open World Survival

Genre: FPS, Multiplayer, Survival

# Devblog 1 - 24/07/2018

- Implemented Inventory System
- Added inventory item stacking
- Game Scene reverted to prototype cubes to preserve optimization
- Removed use of singleton scripts to enable multiplayer functionality (Resulting in a drop in memory usage during runtime)
- Added new (primitive) modular weapons system
- Added weapon reloading
- Added 2 types of ammunition (both for testing for the time being). 5.56 and 7.62
- Added camera bob when jumping/landing

# Devblog 2 - 24/08/2018
- Implemented weapon swaying
- Implemented item stacking UI (Stack sizes are now visible)
- Implemented weapon states (Safety, Single, Automatic) Along with UI
- Implemented weapon aiming
- Players with full inventories cannot pick up more than they can hold (Armour Slot overflow fix)
- Implemented a crafting system with UI
