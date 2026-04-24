# Requirements — "The Precinct" game testing

## 1. Overview
This document defines expected behavior of core gameplay systems.

---

## 2. Functional Requirements

### 2.1 Callout System
- The system should generate random callouts during patrol
- The player should be able to accept or ignore callouts
- The system should assign different types of incidents:robbery and kill of officer

---

### 2.2 Player Actions
- The player should be able to move freely in the open world
- The player should be able to interact with suspects
- The player should receive rewards (Support Tokens) for successful actions

---

### 2.3 AI Behavior — Suspects
- NPC suspects should attempt to escape when detected
- NPC suspects should react to player proximity
- NPC suspects should navigate around obstacles without getting stuck

---

### 2.4 AI Behavior — Partner
- The partner should follow the player
- The partner should assist during pursuits
- The partner should not remain idle during active scenarios

---

### 2.5 Support System
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
