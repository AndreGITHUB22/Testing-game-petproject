# Requirements — "The Precinct" game testing

## 1. Overview
This document defines expected behavior of core gameplay systems.

---

## 2. Functional Requirements

### 2.1 Vehicle Driving System


The system shall allow the player to enter a vehicle when the player is near it<br>
The system shall allow the player to exit the vehicle only when the vehicle is not moving<br>
The system shall allow the player to drive the vehicle forward and backward<br>
The system shall allow the player to turn the vehicle left and right<br>
The system shall prevent the player from entering another vehicle while already inside one<br>
### 2.2 Inventory System


The system shall allow the player to add weapons to the inventory<br>
The system shall limit the inventory capacity (e.g., maximum 5 weapon slots)<br>
The system shall prevent adding weapons when the inventory is full<br>
The system shall allow the player to remove weapons from the inventory<br>
### 2.3 Weapon Equip System


The system shall allow the player to equip a weapon from the inventory<br>
The system shall allow the player to switch between available weapons<br>
The system shall allow the player to unequip (hide) the current weapon<br>
The system shall prevent equipping a weapon if the inventory is empty<br>
### 2.4 Weapon Storage System


The system shall allow the player to store weapons in the car trunk<br>
The system shall allow the player to retrieve weapons from the car trunk<br>
The system shall allow the player to store weapons in the police station<br>
The system shall allow the player to retrieve weapons from the police station<br>
### 2.5 Vehicle Customization


The system shall allow the player to change the vehicle color<br>
The system shall allow the player to select different siren models<br>
The system shall allow the player to change the vehicle model<br>
The system shall provide a preview of customization changes before applying them<br>
The system shall save customization changes after application<br>
The system shall prevent customization if no vehicle is selected<br>
### 2.6 Character Customization


The system shall allow the player to change the character outfit<br>
The system shall allow the player to equip and remove glasses<br>
The system shall allow the player to equip and remove headwear<br>
The system shall apply changes immediately after selection<br>
The system shall save character customization after application<br>

### 2.7 Support System
- The player should be able to request backup
- The system should spawn backup units after request
- Backup units should assist in resolving incidents

---

## 3. Non-Functional Requirements

### 3.1 Performance
- The game should maintain a frame rate of at least 30 FPS on the "Steam Deck" graphics preset during normal gameplay


---

### 3.2 Usability
- UI prompts should be clear and understandable
- Player actions should have visible feedback

---

## 4. Edge Case Requirements
- The system should handle multiple simultaneous callouts
- The system should not break when player ignores objectives
- AI should behave consistently under stress conditions
