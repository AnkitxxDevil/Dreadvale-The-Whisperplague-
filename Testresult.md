# ✅ Test Results – Dreadvale: The Whisperplague

*Project by DevilSyntax Studios*  
*Engine: Unreal Engine 5.3*  
*Status: Active Development*  

---

## 🧪 Test Phase 1 – May 30, 2025

**Build:** v0.1.3-dev  
**Tested By:** Ankit Sharma  
**World Seed:** #3045

---

### ✅ Player Movement

- [x] Walk/Run forward & backward – Working  
- [x] Sprint toggle – Working  
- [x] Jump & crouch – Working  
- [ ] Climb over ledges – ❌ Not yet implemented  

---

### 👻 Enemy AI

- [x] Patrol pathfinding – Working  
- [x] Player detection in line of sight – Working  
- [ ] Ghost phase-through walls – ⚠️ Glitching on steep terrain  

---

### 🌌 World Features

- [x] Day/Night cycle – Working  
- [ ] Fog intensity during night – ⚠️ Too dense  
- [x] Procedural generation – Working  

---

### 🚙 Vehicle System

- [x] Spawning – Working  
- [ ] Handling physics – ⚠️ Slippery on slopes  
- [ ] Customization UI – ❌ Not implemented yet  

---

### 🔫 Weapons

- [x] Melee weapon swing – Working  
- [ ] Firearm projectile accuracy – ⚠️ Slight delay  
- [ ] Weapon switching – ❌ In progress  

---

### 🐛 Bugs Identified

| ID       | Description                        | Status         |
|----------|------------------------------------|----------------|
| BUG-001  | AI gets stuck on cliff corners     | ✅ Fixed        |
| BUG-002  | Player can fall through stairs     | ✅ Fixed        |
| BUG-003  | Fog flickers during sunrise        | ❌ Not fixed    |

---

### 📦 Notes

- Build stable for internal demo.  
- Vehicle physics tuning required.  
- Lighting pass needed on all night zones.  

---

## 🧪 Test Phase 2 – June 03, 2025

**Build:** v0.2.0-alpha  
**Tested By:** Ankit Sharma  
**World Seed:** #7225-F

---

### ✅ Systems Tested

| Feature                       | Status       | Notes                                                      |
|------------------------------|--------------|------------------------------------------------------------|
| Procedural Generation        | ✅ Stable     | Terrain loads consistently with reduced overlap errors     |
| Day/Night Cycle              | ✅ Improved   | Fixed ambient flickering issues during dawn transitions    |
| Enemy AI (Wraith)            | ⚠️ Partial    | AI still glitches on steep incline terrain                 |
| Magical Beast Behavior       | ✅ Working    | Tracking and random roaming verified                       |
| Player Movement              | ✅ Stable     | Smooth navigation, minor slope stutter fixed               |
| Modern Vehicle Spawning      | ✅ Working    | Vehicles spawn in designated safe zones                    |
| Customization UI             | ❌ Not Started| Feature pending development phase                          |
| Combat Mechanics (Prototype) | ⚠️ Testing    | Melee response good, ranged targeting slightly delayed     |

---

### 🐛 Notable Bugs

| ID       | Description                             | Status       |
|----------|-----------------------------------------|--------------|
| BUG-007  | Spectral AI stuck on small boulders     | Known        |
| BUG-010  | Vehicle flips when colliding at angles  | In Progress  |
| BUG-013  | Fog shadow flickers at night            | ✅ Fixed      |
| BUG-014  | Ghosts ignore flashlight in close range | Under Review |

---

### 📦 Artifacts Collected

-🕜SOON

---

### 🧠 Summary

Phase Two focused on AI behavior, terrain generation consistency, and early combat mechanics. Vehicles are stable in their spawn/drive phase, though still need physics tuning. Night cycle lighting is much improved. Fog and enemy interaction continue to need polish.

> **Next Goal:** Implement enemy group tactics, complete ranged combat, and begin multiplayer groundwork.

> _“Every shadow now watches back.”_

---
