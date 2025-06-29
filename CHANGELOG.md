# 📘 Changelog – Dreadvale: The Whisperplague

All notable changes to this project will be documented in this file.  
This project adheres to [Semantic Versioning](https://semver.org/).

---

## [0.2.2-alpha] – 2025-06-29
### Added
- Ranged combat system 
- Weather system with rain and wind effects
- Melee combo system (3-hit sequence with stagger)
- Firearm targeting prototype with preliminary accuracy logic
- Ghosts now react to flashlight exposure

### Fixed
- Ambient light flicker at dawn resolved
- Player slope movement smoothened further
- Ghost AI phase-through logic refined using improved nav mesh

### Changed
- Vehicle traction logic improved on default terrain types
- Magical Beast AI partially optimized for roaming and attack flow

### Known Issues
- Vehicle still slides on sand-based terrain
- Magical Beast animations stutter during attack sequences
- Hitbox offset while sprint-firing with firearms
- Weather particles clipping through interior meshes

---

## [0.2.0-alpha] – 2025-06-03
### Added
- Magical Beast enemy class with patrol and chase behavior
- Vehicle system: spawnable modern vehicles with base physics
- Improved procedural terrain generation with better seed consistency
- Enhanced day/night lighting with smoother transitions

### Fixed
- Fog flicker issue during night transitions
- Player stutter on slope movement
- Cliffside generation errors in procedural world

### Changed
- AI detection system upgraded for better line-of-sight behavior
- Melee hit system restructured to allow dynamic combat responses

### Known Issues
- Ranged combat projectile delay
- Vehicles flip when colliding at sharp angles
- AI stuck on certain boulder types
- Ghosts ignore flashlight close-range

---

## [0.1.3-dev] – 2025-05-29
### Added
- Initial player movement (walk, sprint, crouch, jump)
- Ghost enemy with basic patrol and detection logic
- Melee weapon swing test system
- Procedural world base layer with random seed #3045
- Day/Night cycle with fog control

### Fixed
- Player falling through stairs
- AI pathfinding bugs on cliff corners

### Known Issues
- Fog flicker at sunrise
- Ghosts glitching on terrain slopes
- Customization UI not implemented

---

## 📅 Upcoming Features
- ✅ Full ranged weapon system (aim, fire, reload)
- ✅ Customization menu for vehicles and characters
- ✅ Multiplayer framework initialization
- ✅ Ledge climbing and vaulting system
- ✅ Advanced AI pack behavior

---

> Made with ☠️ by DevilSyntax Studios  
> _“Light fades. Dread remains.”_
> 
