# Evershade Series - Proof of Concept Design Document
**Version:** 1.0  
**Date:** January 2026  
**Project:** Evershade Series Visual & Gameplay Design Concepts

---

## Table of Contents
1. [Executive Summary](#executive-summary)
2. [Visual Identity & Art Direction](#visual-identity--art-direction)
3. [Character Designs](#character-designs)
4. [Environment Concepts](#environment-concepts)
5. [UI/HUD Design](#uihud-design)
6. [Faction Visual Identity](#faction-visual-identity)
7. [Weapons & Equipment](#weapons--equipment)
8. [Titan Mech Designs](#titan-mech-designs)
9. [Level Layout Concepts](#level-layout-concepts)
10. [Technical Implementation Notes](#technical-implementation-notes)

---

## Executive Summary

This document presents comprehensive proof of concept designs for the Evershade game series, focusing on visual development, gameplay mechanics illustration, and art direction. The Evershade universe blends **Gothic architecture with futuristic sci-fi**, creating a unique aesthetic that sets it apart from traditional space-themed games.

### Core Design Principles
- **Gothic Sci-Fi Fusion**: Victorian-era architecture meets advanced technology
- **Asymmetrical Design**: Each faction has distinct visual language
- **Atmospheric Tone**: Dark, moody, with dramatic lighting
- **Tactical Clarity**: Despite visual complexity, gameplay readability is paramount

### Deliverables in This Package
- Character concept designs (Pilots, Titans, Aliens)
- Environment concept illustrations
- UI/HUD mockups for both RTS and FPS games
- Faction visual identity guides
- Weapon and equipment designs
- Titan mech specifications
- Level layout concepts with gameplay flow
- Color palettes and style guides

---

## Visual Identity & Art Direction

### Color Palette Philosophy

#### Human Aegis Fleet
**Primary Colors:**
- Deep Navy Blue (#1A2332)
- Steel Gray (#5D6D7E)
- Gold Accent (#D4AF37)
- Warning Red (#C0392B)

**Usage:**
- Navy for primary surfaces
- Steel for mechanical components
- Gold for insignia and highlights
- Red for alert states

#### Crystal Ravagers
**Primary Colors:**
- Ethereal Purple (#8E44AD)
- Crystal Blue (#3498DB)
- Pale Violet (#E8DAEF)
- Dark Obsidian (#1C1C1C)

**Usage:**
- Purple glow for crystal elements
- Blue for energy weapons
- Pale violet for atmospheric effects
- Obsidian for armor plating

### Lighting Philosophy
- **Dramatic Contrast**: Deep shadows with bright highlights
- **Atmospheric**: Volumetric fog and God rays
- **Color Temperature**: Cool blues for tech, warm ambers for human spaces
- **Dynamic**: Day/night cycles and battle lighting changes

### Architecture Style
- **Neo-Gothic**: Flying buttresses, pointed arches, rose windows
- **Industrial**: Exposed machinery, riveted metal, steam vents
- **Monumental Scale**: Buildings that dwarf human scale
- **Decay**: Weathering, battle damage, organic overgrowth

---

## Character Designs

### Human Characters

#### Lieutenant Orion "Shadow" Ward (Protagonist - Shadow War)
**Role:** Elite Pilot, Player Character  
**Age:** 28  
**Personality:** Determined, resourceful, develops bond with AI

**Physical Design:**
```
Height: 6'0" (183 cm)
Build: Athletic, lean muscle
Hair: Dark brown, military short
Eyes: Gray-blue
Defining Features: Scar across left eyebrow from Rancor evacuation
```

**Pilot Suit Design:**
- **Base Layer**: Form-fitting tech-weave undersuit (navy blue)
- **Armor Plating**: Lightweight composite plates on chest, shoulders, thighs
  - Gothic motif: Etched patterns resembling cathedral windows
  - Aegis Fleet emblem on left shoulder
- **Jump Kit**: Sleek backpack unit with twin jet thrusters
  - Telescoping design for compact storage
  - Blue energy glow when active
- **Helmet**: Streamlined with HUD visor
  - Retractable face shield
  - Communication antenna
  - Built-in rebreather

**Visual Reference (ASCII Art):**
```
        [HELMET]
       /|||||||\
      | •    • |  ← Visor with HUD
      |   \/   |
       \______/
          ||
      [SHOULDER]
     ///|ARMOR|\\\
    // [AEGIS] \\
   |   EMBLEM   |
   |____________|
   ||  CHEST  ||
   || PLATE   ||
   ||_________||
    \\ JUMP  //
     \\ KIT //
      \\___//
        ||||
       /|  |\
      / |  | \
    [LEGS] [LEGS]
```

**Color Scheme:**
- Suit: Deep navy (#1A2332)
- Armor: Steel gray (#5D6D7E)
- Accents: Gold trim (#D4AF37)
- Energy: Blue glow (#3498DB)

#### Admiral Helena Solari
**Role:** Fleet Commander (appears in both games)  
**Age:** 52  
**Personality:** Strategic, compassionate, burden of command

**Uniform Design:**
- **Traditional Naval Coat**: Long, tailored with gothic elements
  - High collar with gold braiding
  - Epaulettes with rank insignia
  - Double-breasted with ornate buttons
- **Color**: Deep navy with gold trim
- **Accessories**: Command staff, holographic data-pad
- **Details**: Medals from previous campaigns

---

### Alien Characters

#### Crystal Ravagers - Infantry Design

**Crusader (Basic Unit):**
```
Visual Concept:
       /\
      /  \
     |••••|  ← Crystalline head/helm
     |    |
    /|☆☆☆|\  ← Glowing crystal core
   | |    | |
   | |____| |
   |/|    |\|
    ||    ||
    ||    ||
   /  \  /  \
```

**Design Features:**
- **Body Structure**: Humanoid but with crystalline geometry
- **Head**: Angular, no visible face, two glowing "eyes"
- **Core**: Exposed chest crystal that pulses with energy
- **Armor**: Victorian-inspired plate with crystal inlays
  - Pauldrons with filigree patterns
  - Segmented limbs for mobility
- **Colors**: Purple glow (#8E44AD) on obsidian base (#1C1C1C)

**Crystal Knight (Elite Melee Unit):**
- **Height**: 7'2" (taller than humans)
- **Weapon**: Crystal blade that hums with energy
- **Armor**: Heavy plate with ceremonial elements
  - Cape/cloak of crystalline shards
  - Crown-like head piece
- **Movement**: Graceful but powerful, like a dancer

#### Crystal Ravagers - Leadership

**Crystal General (Boss Character):**
```
Design Concept:
         ///\\\\
        ///☆☆\\\\ ← Crown of floating crystals
       ///    \\\
      ||| ʘ  ʘ |||  ← Large glowing eyes
      |||      |||
      |||  \/  |||
       \\\____///
          ||||
     /////////////
    /// ORNATE ///
   ///  ARMOR  ///
  ///           \\\ ← Cape of energy
 ///             \\\
```

**Characteristics:**
- **Imposing Presence**: 8 feet tall
- **Ornate Armor**: Gothic Victorian general's uniform in crystal
- **Floating Elements**: Crystal shards orbit the body
- **Voice**: Deep, aristocratic, echoing
- **Weapons**: Energy saber and crystal-tech staff

---

## Environment Concepts

### Neo-Gothic Human Cities

#### New Bastion (Capital City - Pre-Destruction)
**Architectural Style:** Gothic Revival meets Advanced Tech

**Key Features:**
```
SKY PROFILE:
   ╱╲        ╱╲       ╱╲
  ╱  ╲      ╱  ╲     ╱  ╲
 ╱SPIRE╲   ╱TOWER╲  ╱SPIRE╲
╱______╲  ╱______╲ ╱______╲
|      |  |      | |      |
|GOTHIC|  |CATHE-| |GOTHIC|
|TOWERS|  | DRAL | |TOWERS|
|======|  |======| |======|
|FLYING |  |      | |      |
|BUTTRS |  |      | |      |
========  ======== ========
```

**Environmental Details:**
- **Streets**: Wide boulevards with cobblestone (enhanced durability)
- **Lighting**: 
  - Day: Natural light through stained glass
  - Night: Bioluminescent street lamps (gothic lamp posts)
- **Atmosphere**: Mist from industrial vents creates mystery
- **Vertical Design**: Multiple levels connected by bridges

#### The Pale City (Ruined Combat Zone - Shadow War)
**Post-Battle Environment**

**Atmospheric Conditions:**
- Constant drizzle/rain for mood
- Smoke from fires
- Broken infrastructure leaking steam
- Dawn/dusk lighting (golden hour)

**Destruction Patterns:**
```
RUINED BUILDING PROFILE:
     /\  [missing section]
    /XX\___
   /XXXXXX\
  /XXX||XXX\
 /XXXX||XXXX\
|XXXXX||XXXXX| ← Half-destroyed gothic tower
|XXXXX||XXXXX|
|=====||=====|
|  ||    ||  | ← Broken floors
|  ||    ||  |
[RUBBLE][RUBBLE]
```

**Gameplay Zones:**
- **Rooftops**: Pilot parkour routes
- **Streets**: Titan combat lanes (wide enough for mechs)
- **Interiors**: Close-quarters combat
- **Collapsed Sections**: Verticality and cover

---

### Alien Environments

#### Crystal Ravager Capital Ship Interior
**Design Philosophy:** Organic Crystal Cathedral

**Visual Description:**
```
CORRIDOR CROSS-SECTION:
        /☆☆☆\
       /     \
      / GLOW \
     /   ☆   \
    ___________
   |           | ← Crystalline walls
   | ☆       ☆ | ← Embedded light crystals
   |           |
   |    ☆ ☆    |
   |           |
   |___________|
```

**Characteristics:**
- **Walls**: Translucent crystal with inner light
- **Floor**: Smooth obsidian with crystal veins
- **Ceiling**: Cathedral vaulting with crystal chandeliers
- **Acoustics**: Eerie echo, ambient humming from crystals
- **Color**: Purple and blue bioluminescence

**Architectural Elements:**
- Gothic arches made of crystal
- Rib vaulting that appears grown, not built
- "Stained glass" effect from crystal refractions
- Pulsing light suggesting the ship is "alive"

---

## UI/HUD Design

### Siege of Rancor (RTS) - UI Design

#### Main HUD Layout
```
╔════════════════════════════════════════════════════════════╗
║ [RESOURCES]         EVERSHADE: SIEGE OF RANCOR    [MINI]  ║
║ ⚡ Energy: 1250    ════════════════════════    [  MAP  ]  ║
║ 🔧 Metal: 850                                  [       ]  ║
║ 👥 Pop: 45/100                                 [       ]  ║
╠════════════════════════════════════════════════════════════╣
║                                                            ║
║                  [MAIN GAME VIEW]                         ║
║                                                            ║
║                    [BATTLEFIELD]                          ║
║                                                            ║
║                  [UNIT SELECTION AREA]                    ║
║                                                            ║
╠════════════════════════════════════════════════════════════╣
║ [SELECTED UNIT INFO]        [ACTION BUTTONS]         [⚙️] ║
║ ┌──────────────┐            ╔═╗ ╔═╗ ╔═╗ ╔═╗              ║
║ │ UNIT PORTRAIT│            ║⚔║ ║🛡║ ║🔧║ ║⚡║              ║
║ │  [AEGIS-1]  │            ╚═╝ ╚═╝ ╚═╝ ╚═╝              ║
║ └──────────────┘                                          ║
║ HP: ████████░░ 80%          PRODUCTION QUEUE:            ║
║ Shield: ██████░░░░ 60%      [CRUISER] [FIGHTER] [TITAN] ║
╚════════════════════════════════════════════════════════════╝
```

**Design Elements:**
- **Color Scheme**: Dark blue (#1A2332) background with gold (#D4AF37) borders
- **Typography**: Military stencil font for headers, clean sans-serif for data
- **Icons**: Minimalist, high contrast for quick recognition
- **Animations**: Subtle pulse on active elements

#### Resource Display Details
```
ENERGY DISPLAY:
⚡ 1250  [████████░░] +150/sec
   └─ Icon  └─ Bar    └─ Rate

METAL DISPLAY:
🔧 850   [█████░░░░░] +75/sec

POPULATION:
👥 45/100 [██████░░░░] +0
```

#### Unit Selection Panel
```
MULTIPLE UNITS SELECTED:
┌─────────────────────────────────┐
│ [⚔][⚔][⚔][⚔][⚔]  x5 Fighters  │
│ HP: ████░ Avg: 82%              │
│ [⬆Move] [⚔Attack] [🛡Defend]   │
└─────────────────────────────────┘

SINGLE UNIT SELECTED:
┌─────────────────────────────────┐
│      [UNIT PORTRAIT]            │
│   AEGIS BATTLE CRUISER          │
│                                 │
│ HP:    ████████░░  85%          │
│ Shield: ██████████ 100%         │
│ Energy: ████████░░  80%         │
│                                 │
│ Weapons: [ONLINE]               │
│ - Plasma Cannons    [READY]     │
│ - Missile Pods      [RELOAD]    │
│ - Point Defense     [ACTIVE]    │
│                                 │
│ [⚔ATK] [🛡DEF] [🔧REP] [⚡PWR]  │
└─────────────────────────────────┘
```

---

### Shadow War (FPS) - HUD Design

#### Pilot Mode HUD
```
         [COMPASS: N]
              ^
              |

WEAPON:                         HEALTH/SHIELD:
MK8 REAPER                      ████████░░ SHIELD: 80
[||||||||||||]                  ██████████ HEALTH: 100
AMMO: 28/120                    
                                TACTICAL:
THREAT DETECTOR:                [CLOAK: READY]
    o                           [CHARGE: 75%]
   /|\
  o o o  ← Enemy positions

OBJECTIVE:
► Destroy Comm Tower [450m]

TITAN STATUS:
[AEGIS-7] READY
Press [Q] to call Titan
```

**Design Specifications:**
- **Position**: Minimal, non-intrusive
- **Color**: White text with blue accents
- **Opacity**: 70% baseline, 100% when relevant
- **Dynamic Elements**: Flash red on damage, pulse on ability ready

#### Titan Mode HUD
```
╔═══════════════════════════════════════════════════════════╗
║                     [TACTICAL VIEW]                       ║
║         ________________________________________          ║
║        |                                        |         ║
║        |         AEGIS-7 TITAN MODE            |         ║
║        |________________________________________|         ║
║                                                           ║
╠═══════════════════════════════════════════════════════════╣
║ WEAPON SYSTEM:                   ARMOR INTEGRITY:        ║
║ 40mm CANNON                      ████████████░░ 85%      ║
║ [████████████████░░░░] READY     FRONT:  ████████░░ 90% ║
║ AMMO: 16/64                      SIDES:  ██████████ 100%║
║                                   REAR:   ████████░░ 80% ║
║ ORDNANCE:                                                 ║
║ MISSILE SALVO [████████] READY   CORE ABILITY:           ║
║                                   [████████░░░░] 80%      ║
║ DEFENSIVE:                        SALVO CORE - READY     ║
║ SHIELD [██████] AVAILABLE                                ║
║                                                           ║
║ DASH: [▓] [▓] AVAILABLE          THREAT SCAN:            ║
║                                   ENEMY TITAN: 150m NW   ║
║ [EJECT] Hold [E] for 3 seconds   12 HOSTILES DETECTED   ║
╚═══════════════════════════════════════════════════════════╝
```

**Titan HUD Features:**
- **Cockpit Frame**: Visible edges suggesting interior view
- **Armor Diagram**: Directional damage indicator
- **Core Meter**: Prominent, fills during combat
- **Audio Cues**: Titan AI voice announces status
- **Targeting**: Auto-lock indicators for other Titans

#### Damage States

**Pilot Taking Damage:**
```
NORMAL VIEW:
[Clear vision, full color]

SHIELD BREAKING:
[Blue crackling overlay]
*BZZT* Shield depleted!

LOW HEALTH:
[Red vignette at edges]
[Heartbeat sound increases]
[Screen slightly desaturated]

CRITICAL:
[Heavy red pulse]
[Blurred vision]
[Seek medical attention!]
```

**Titan Critical State:**
```
╔═══════════════════════════════════════════════════════════╗
║ ⚠️  CRITICAL DAMAGE  ⚠️                                   ║
║                                                           ║
║ ARMOR: ██░░░░░░░░░░ 15% [CRITICAL]                       ║
║                                                           ║
║ ⚠️  SYSTEM FAILURES:                                      ║
║ - LEFT ARM: OFFLINE                                       ║
║ - SHIELD: DESTROYED                                       ║
║ - DASH: DAMAGED                                           ║
║                                                           ║
║ RECOMMENDATION: EJECT IMMEDIATELY                         ║
║                                                           ║
║ [EJECT] HOLD [E] TO EJECT  ⏱️ 5...4...3...              ║
╚═══════════════════════════════════════════════════════════╝
```

---

## Faction Visual Identity

### Human Aegis Fleet

#### Logo Design
```
        ╔═══════╗
       ╔╝       ╚╗
      ╔╝  ╱═══╲  ╚╗
     ╔╝  ║ ☆ ☆ ║  ╚╗
    ║    ║  ◇  ║    ║
    ║    ║ ☆ ☆ ║    ║
     ╚╗  ╚═════╝  ╔╝
      ╚╗    ║    ╔╝
       ╚╗   ║   ╔╝
        ╚═══╩═══╝
        
   AEGIS FLEET
  Humanity's Shield
```

**Logo Elements:**
- **Shield Shape**: Protection symbolism
- **Stars**: Four points representing fleet divisions
- **Diamond**: Unity and strength
- **Gothic Border**: Architectural heritage

**Usage Guidelines:**
- **Colors**: Gold on navy, or white on dark backgrounds
- **Placement**: Left shoulder on uniforms, ship hulls, buildings
- **Variations**: Simplified version for small applications

#### Ship Design Language
**Aesthetic:** Cathedral-Ships

**Design Principles:**
- **Silhouette**: Vertical emphasis, spires and towers
- **Hull**: Armored plates with Gothic arch patterns
- **Engines**: Blue plasma drives at stern
- **Weapons**: Turrets integrated into architecture
- **Details**: Flying buttresses as structural elements

**Example Ship Cross-Section:**
```
         /\
        /  \
       /SPIRE\
      /______\
     /|      |\
    / |BRIDGE| \
   /  |______|  \
  /   ||||||    \
 /    ||||||     \
/__________________\
|     HANGAR      |
|    [LAUNCH]     |
|__________________|
|||||||||||||||||||| ← Armor Belt
[ENGINE] [ENGINE]
  ||||      ||||
  Blue      Blue
```

---

### Crystal Ravagers

#### Faction Emblem
```
        ☆
       ╱ ╲
      ╱   ╲
     ☆     ☆
     ║     ║
     ║  ☆  ║
     ║ ╱ ╲ ║
     ║╱   ╲║
     ☆     ☆
      ╲   ╱
       ╲ ╱
        ☆

  CRYSTAL RAVAGERS
  Eternal Dominion
```

**Emblem Characteristics:**
- **Crystalline Structure**: Seven-pointed star arrangement
- **Symmetry**: Perfect geometric balance
- **Glow**: Pulsing purple light
- **Material**: Appears carved from single crystal

#### Ship Design Language
**Aesthetic:** Living Crystal Cathedrals

**Design Principles:**
- **Organic Growth**: Ships appear grown, not built
- **Translucency**: Partial see-through with internal glow
- **Asymmetry**: Unlike human symmetry, more naturalistic
- **Spires**: Multiple crystal formations jutting from hull
- **Color**: Purple, blue, and obsidian

**Example Ship Profile:**
```
    ☆     ☆    ☆
    |     |    |
   /|\   /|\  /|\
  / | \ / | \/ | \
 /  |  ☆  |  \ |  \
☆   |  |  |   \|   ☆
 \  | /  \|  / |  /
  \ |/    | /  | /
   \|    \|/   |/
    ☆     ☆    ☆
    |     |    |
  [CRYSTAL CORE]
    |     |    |
    ☆     ☆    ☆
```

---

## Weapons & Equipment

### Human Pilot Weapons

#### MK8 "Reaper" Assault Rifle
**Classification:** Standard Issue Infantry Rifle

**Specifications:**
```
LENGTH: ═══════════════════════════╗
               28 inches             ║
                                     ║
PROFILE VIEW:                        ║
 [SIGHT]                             ║
   |||                               ║
━━━╱=╲━━━━━━━━━━━━━━━━━━━╗          ║
   |▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓║ ← Barrel ║
   |▓▓[AMMO COUNTER]▓▓▓▓▓║          ║
━━━╲_╱━━━━━━━━━━━━━━━━━━━╝          ║
  ║   ║                              ║
[GRIP][TRIGGER]                      ║
  ║                                  ║
[MAGAZINE]                           ║
  ╚══════════════════════════════════╝
```

**Technical Details:**
- **Caliber**: 7.62mm caseless
- **Fire Rate**: 750 RPM (burst/auto modes)
- **Magazine**: 30 rounds
- **Effective Range**: 400m
- **Special Feature**: Digital ammo counter on receiver

**Design Elements:**
- **Color**: Gunmetal gray with gold Aegis emblem
- **Furniture**: Polymer grips with texture for glove compatibility
- **Sights**: Holographic with 2x zoom
- **Customization**: Rail system for attachments

#### "Thunderbolt" Shotgun
**Classification:** Close Quarters Combat

**Specifications:**
```
SIDE VIEW:
 [SIGHT]
   |||
━━━╱=╲━━━━━━━━━━╗
   |▓▓▓▓▓▓▓▓▓▓▓║ ← Short barrel
   |▓▓▓[PUMP]▓▓║
━━━╲_╱━━━━━━━━━━╝
  ║   ║
[GRIP][TRIGGER]
  ║
[TUBE MAGAZINE]
  ╚══════════════════
```

**Technical Details:**
- **Gauge**: 12 gauge
- **Capacity**: 8 shells
- **Action**: Pump
- **Spread**: Tight choke for precision
- **Special**: Can load slug rounds for doors/walls

#### Anti-Titan Missile Launcher
**Classification:** Heavy Ordnance

**Specifications:**
```
LAUNCHER PROFILE:

      [TARGETING RETICLE]
           |||
     ╔═════╧═════╗
     ║  MISSILE  ║ ← Loaded missile visible
     ║           ║
     ╚═══════════╝
━━━━━━━━╱=========╲━━━━━
        |▓▓▓▓▓▓▓▓▓|
        |▓▓▓▓▓▓▓▓▓|
━━━━━━━━╲=========╱━━━━━
        ║    ║
     [GRIP][TRIGGER]
        ║
   [FIRE CONTROL]
```

**Technical Details:**
- **Missiles**: Lock-on guided
- **Capacity**: 1 ready, 3 reserve
- **Lock Time**: 2.5 seconds
- **Damage**: High explosive shaped charge
- **Special**: Can dumb-fire without lock

---

### Titan Weapons

#### 40mm Autocannon
**Classification:** Main Battle Weapon

**Specifications:**
```
TITAN ARM MOUNT:

  [TITAN ARM]
      ║ ║
      ║ ║
    ╔═╩═╩═╗
    ║MOUNT║
    ╚═╦═╦═╝
      ║ ║
  ━━━━╧═╧━━━━━━━━━━━━━━━╗
  ║  [40mm CANNON]      ║
  ║  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ ║
  ║  [DRUM MAGAZINE]    ║
  ━━━━━━━━━━━━━━━━━━━━━━╝
          ║ ║
      [STABILIZERS]
```

**Technical Details:**
- **Caliber**: 40mm explosive shells
- **Fire Rate**: 120 RPM
- **Capacity**: 16 rounds (drum magazine)
- **Reload**: 3.5 seconds
- **Effective Range**: 800m
- **Damage**: High splash, excellent vs. infantry and light armor

**Visual Design:**
- **Construction**: Heavy industrial, riveted panels
- **Color**: Dark gray with warning stripes (yellow/black)
- **Details**: Brass shell ejection port, smoke vents

#### Missile Pod System
**Classification:** Ordnance

**Mounted on Titan shoulder:**
```
MISSILE POD:

  ╔══════════════╗
  ║ [][] [][] [][] ║ ← 12 missiles in 4x3 grid
  ║ [][] [][] [][] ║
  ║ [][] [][] [][] ║
  ║ [][] [][] [][] ║
  ╚══════════════╝
       ╱║║╲
      ╱ ║║ ╲
     ╱  ║║  ╲
    ╱   ║║   ╲
   ╱    ║║    ╲
  [TITAN SHOULDER]
```

**Technical Details:**
- **Missiles**: Micro-missiles, tracking
- **Salvo**: 12 missiles in rapid sequence
- **Reload**: Requires supply drop or base
- **Guidance**: Swarm logic, multiple targets
- **Damage**: Moderate per missile, devastating salvo

---

### Crystal Ravager Weapons

#### Crystal Rifle
**Classification:** Energy Weapon

**Design Concept:**
```
ALIEN ENERGY WEAPON:

        ☆ ← Energy focus crystal
       ╱╲
      ╱  ╲
     ☆    ☆ ← Secondary crystals
     ║    ║
━━━━━╬════╬━━━━━━━━━━╗
     ║▓▓▓▓║  CRYSTAL  ║
     ║▓▓▓▓║  MATRIX   ║
━━━━━╬════╬━━━━━━━━━━╝
     ║    ║
    [GRIP]
     ║
    ☆☆☆ ← Power core
```

**Technical Details:**
- **Type**: Directed energy beam
- **Color**: Purple/blue energy bolt
- **Rate**: 180 RPM (bolt action)
- **Heat**: Overheats after 15 shots
- **Special**: Pierces light cover
- **Sound**: Musical chime/crystal ringing

**Visual Characteristics:**
- **Material**: Translucent crystal with obsidian frame
- **Glow**: Pulses with energy charge
- **Elegance**: Ornate, almost ceremonial appearance
- **Organic**: Grown rather than manufactured look

---

## Titan Mech Designs

### Aegis-7 (Player Titan - Shadow War)

#### Overall Design Philosophy
**Concept:** Knight-Meets-War-Machine

**Height:** 20 feet (6.1 meters)  
**Weight:** 18 tons  
**Classification:** Medium Assault Titan

#### Full Body Schematic
```
       [HEAD]
      /|||||||\
     | ● ══ ● | ← Optical sensors
     |   \/   |
      \______/
         ║║
    ╔═══╬╬═══╗
    ║   ╚╝   ║ ← Torso
    ║  AEGIS ║
    ║   7    ║
    ║        ║
    ╠════════╣
   ╔╝        ╚╗
  ╔╝  [CORE]  ╚╗ ← Reactor visible
 ╔╝   ☢️    ☢️  ╚╗
╔╝              ╚╗
║  LEFT     RIGHT ║
║  ARM       ARM  ║
║  ║         ║    ║
║  ║ [40mm]  ║    ║ ← Weapons
║  ║ [CANNON]║    ║
║  ║         ║    ║
╚═╗║         ║╔═╝
  ╚╗        ╔╝
   ╚════════╝
      ║  ║
   [HIPS/JOINTS]
      ║  ║
   ╔══╩══╩══╗
  ╔╝ [LEGS] ╚╗
 ╔╝          ╚╗
╔╝            ╚╗
║  HYDRAULIC   ║
║  ACTUATORS   ║
╚══╗        ╔══╝
  ╔╝        ╚╗
 ╔╝  [FEET]  ╚╗
╔╝            ╚╗
[STABILIZERS]
```

#### Head Design Detail
```
FRONT VIEW:          SIDE VIEW:
   /======\              /╲
  /  ●══●  \            / ║\
 |          |          /  ║ \
 |   [\/]   |         |  [●] | ← Sensor
 |   VENT   |         |   ║  |
  \________/           \__║_/
     ||||                 ║
  [NECK JOINT]      [ARMOR PLATE]
```

**Head Features:**
- **Visor**: Two main optical sensors (glowing blue)
- **Shape**: Angular, helmet-like (knight inspiration)
- **Sensors**: Multi-spectrum targeting array
- **Vents**: Heat dissipation slits
- **Armor**: Heavy frontal plating

#### Torso Design Detail
```
FRONT VIEW:

╔═══════════════════╗
║   CHEST PLATE     ║
║                   ║
║    ╔═══════╗     ║
║    ║ AEGIS ║     ║ ← Emblem
║    ║   7   ║     ║
║    ╚═══════╝     ║
║                   ║
║  [REACTOR VIEW]  ║
║   ☢️ VISIBLE ☢️   ║ ← Glowing core
║   THROUGH GAP    ║
║                   ║
╚═══════════════════╝
      ║     ║
   [WAIST JOINT]
```

**Torso Features:**
- **Chest Plate**: Heavy armor with Aegis insignia
- **Reactor**: Partially exposed (gameplay: weak point)
- **Shoulders**: Broad for weapon mounting
- **Articulation**: Full 360° torso rotation
- **Cockpit**: Centered, armored canopy

#### Arm Design - Weapon Mount
```
LEFT ARM (WEAPON ARM):

  [SHOULDER MOUNT]
        ║║║
    ╔═══╩╩╩═══╗
    ║ SHOULDER ║
    ╚═════╦═══╝
          ║
     ╔════║════╗
     ║  [SERVO] ║ ← Elbow joint
     ╚════╦════╝
          ║
     ╔════║════╗
     ║   ARM   ║
     ║          ║
     ║  ▓▓▓▓▓  ║
     ║ 40mm    ║ ← Integrated weapon
     ║ CANNON  ║
     ║  ▓▓▓▓▓  ║
     ║          ║
     ╚══════════╝
          ║
      [HAND/GRIP]
```

#### Right Arm - Multi-Purpose
```
RIGHT ARM:

     [SHOULDER]
        ║║║
    ╔═══╩╩╩═══╗
    ║ MISSILE  ║ ← Pod mounted
    ║  POD     ║
    ║ [][][]   ║
    ╚═════╦═══╝
          ║
     ╔════║════╗
     ║  SERVO  ║
     ╚════╦════╝
          ║
     ╔════║════╗
     ║   ARM   ║
     ╚════╦════╝
          ║
      ╔═══╩═══╗
      ║ HAND  ║
      ║ ═══   ║ ← 3 fingers + thumb
      ║ ═══   ║
      ║ ═══   ║
      ╚═══════╝
```

#### Leg Design
```
FRONT VIEW:          SIDE VIEW:

    [HIP JOINT]
        ║║                ╔══╗
    ╔═══╩╩═══╗          ╔╝  ╚╗
    ║  THIGH  ║          ║ THIGH║
    ║ ARMOR   ║          ║ SERVO ║
    ║          ║          ╚╗    ╔╝
    ╚════╦════╝           ║    ║
    [KNEE JOINT]      [KNEE JOINT]
    ╔════╩════╗           ║    ║
    ║  SHIN   ║          ╔╝    ╚╗
    ║  ARMOR  ║          ║  LEG  ║
    ║          ║          ║ SERVO ║
    ║ HYDRAULIC║         ╚╗    ╔╝
    ║  STRUTS  ║          ║    ║
    ╚════╦════╝       [ANKLE JOINT]
    [ANKLE JOINT]         ║    ║
    ╔════╩════╗          ╔╝    ╚╗
    ║  FOOT   ║         ╔╝ FOOT ╚╗
    ║ ═════   ║ ← Toes  ║═══════║
    ╚═════════╝         ╚═══════╝
```

**Leg Features:**
- **Hydraulics**: Visible pistons and actuators
- **Armor**: Layered plates on thighs and shins
- **Joints**: Reinforced knees and ankles
- **Feet**: Wide stance for stability, articulated toes
- **Details**: Warning stripes on movable parts

#### Color Scheme & Materials
```
MATERIAL BREAKDOWN:

ARMOR PLATES:
- Primary: Navy Blue (#1A2332)
- Secondary: Steel Gray (#5D6D7E)
- Accents: Gold trim (#D4AF37)

GLOWING ELEMENTS:
- Reactor: Blue-white (#3498DB)
- Sensors: Bright blue (#5DADE2)
- Thrusters: Cyan-blue exhaust

WEATHERING:
- Scratches: Lighter gray showing metal beneath
- Scorch marks: Carbon black from combat
- Dirt: Brown-gray accumulation in joints
```

#### Loadout Variants

**Assault Configuration:**
```
- Primary: 40mm Autocannon (Left Arm)
- Secondary: Missile Pod (Right Shoulder)
- Defense: Energy Shield (Deploy from forearms)
- Core: Salvo Core (Guided missile barrage)
```

**Heavy Configuration:**
```
- Primary: 90mm Cannon (Left Arm)
- Secondary: Mortar (Back Mount)
- Defense: Reactive Armor (Damage reduction)
- Core: Siege Mode (Anchor for max damage)
```

**Light/Fast Configuration:**
```
- Primary: Chaingun (Left Arm)
- Secondary: Close Combat (Right Arm Blade)
- Defense: Phase Dash (Quick repositioning)
- Core: Overdrive (Speed and damage boost)
```

---

### Enemy Titan - Crystal Golem

#### Design Concept
**Type:** Crystalline War Construct

**Height:** 22 feet (larger than human Titans)  
**Design Philosophy:** Organic Crystal Growth

```
       ☆☆☆
      ╱   ╲
     ☆ ⬡ ⬡ ☆ ← Crown of crystals
     ║  \/  ║
      \____/
        ║║
    ☆═══╬╬═══☆
   ╱    ╚╝    ╲
  ╱   CRYSTAL  ╲
 ╱    TORSO    ╲
╱   ☆ CORE ☆    ╲
║               ║
☆               ☆
║    ARM    ARM   ║
║    ☆      ☆    ║
║    ║      ║    ║
║   ENERGY ENERGY ║
║   BLADE  CANNON ║
☆    ☆      ☆    ☆
     ║      ║
   [LEGS]  [LEGS]
     ☆      ☆
```

**Characteristics:**
- **Material**: Translucent purple crystal
- **Core**: Visible glowing heart (weak point)
- **Asymmetry**: Organic, natural look
- **Weapons**: Energy blade and crystal cannon
- **Movement**: Graceful, almost floating gait

---

## Level Layout Concepts

### Shadow War Mission 2: "Ghosts of Rancor"

#### Mission Overview
- **Environment**: Abandoned moon outpost at night
- **Objectives**: Infiltrate, gather intel, escape
- **Gameplay**: Stealth → Combat → Titan Defense

#### Map Layout (Top-Down)
```
╔═══════════════════════════════════════════════════════════╗
║                    [START - LANDING ZONE]                 ║
║                           ↓                               ║
║    FOREST              [CLIFF]              FOREST        ║
║    ╱╲╱╲                  ║                  ╱╲╱╲         ║
║   ╱╲╱╲╱╲              [PATH]              ╱╲╱╲╱╲        ║
║  ╱╲╱╲╱╲╱╲               ║               ╱╲╱╲╱╲╱╲       ║
║                          ↓                                ║
║              ╔═════════════════════╗                      ║
║              ║  OUTPOST PERIMETER  ║                      ║
║              ║  ┌─────────────┐   ║                      ║
║              ║  │  MAIN BASE  │   ║  [GUARD TOWERS]     ║
║              ║  │  ┌───────┐  │   ║       ▲              ║
║  [SIDE]      ║  │  │COMM   │  │   ║       │              ║
║  [ENTRY]◄────║──┼─►│TOWER  │  │   ║       │              ║
║  (stealth)   ║  │  └───────┘  │   ║  [SEARCHLIGHTS]     ║
║              ║  │             │   ║                      ║
║              ║  │  [PRISON]   │   ║                      ║
║              ║  │  [CELLS]    │   ║                      ║
║              ║  └─────────────┘   ║                      ║
║              ║         ↓           ║                      ║
║              ║    [COURTYARD]     ║                      ║
║              ║         ↓           ║                      ║
║              ║  [TITAN DROP ZONE] ║◄─── Combat phase    ║
║              ╚═════════════════════╝                      ║
║                         ↓                                 ║
║                   [EXTRACTION]                            ║
║                      [PAD]                                ║
╚═══════════════════════════════════════════════════════════╝

LEGEND:
───── = Pilot routes (parkour)
═════ = Titan routes (wide paths)
↓↑    = Direction of progression
[ ]   = Key locations
◄►    = Multiple approach options
```

#### Vertical Cross-Section
```
HIGH ROUTE (Rooftops):
╱╲╱╲╱╲  CLIFF  ╱╲╱╲╱╲
              ╱      ╲
            ╱  SNIPER  ╲
           ╱   POSITION  ╲
         ╱________________ ╲
        
MID ROUTE (Ground):
════════════════════════════
[PATROL] [PATROL] [PATROL]
    ↓        ↓        ↓
════════════════════════════

LOW ROUTE (Underground):
____________________________
         [VENTS]
    _______________
   │   TUNNELS    │
   │______________│
```

#### Detailed Section - Comm Tower Area
```
ISOMETRIC VIEW:

        ☆ ← Objective: Comm Tower
       ╱╲
      ╱  ╲
     ╱ ## ╲  ## = Destructible
    ╱  ##  ╲
   ╱   ##   ╲
  ╱____##____╲
  ║    ##    ║
  ║  [ROOM]  ║
  ║ [INTEL]  ║
  ╚═════╦═══╝
        ║
   BUILDING
   ┌────║────┐
   │    ║    │
   │  STAIRS │
   │    ║    │
   └────╨────┘
      GROUND
═══════════════════

APPROACH OPTIONS:

OPTION A - STEALTH:
Player climbs side wall →
Enter via window →
Silent takedown guards →
Reach comm tower

OPTION B - LOUD:
Call Titan →
Titan breaches wall →
Fight through →
Reach tower

OPTION C - MIXED:
Disable alarm →
Sneak to tower →
Plant charges →
Escape in Titan
```

#### Enemy Placement - Stealth Phase
```
PATROL PATTERNS:

    1️⃣ ← Guard 1 route
     ╲
      ╲
       ▼
    ●───●───●
    ↑       ↓
    ●   3️⃣  ●
    ↑       ↓
    ●───●───●
        ↑
       ╱
      ╱
    2️⃣ ← Guard 2 route

🔦 = Searchlight (sweeping pattern)
👁️ = Camera (fixed cone of vision)
🚶 = Patrol path
```

---

### Siege of Rancor - Mission: "Defense of New Bastion"

#### Strategic Map
```
═══════════════════════════════════════════════════════════
                    [SPACE ABOVE]
        CRYSTAL FLEET           AEGIS FLEET
             ▼▼▼                   ▲▲▲
        (ATTACKING)           (DEFENDING)
═══════════════════════════════════════════════════════════
                 ORBITAL LAYER
    [DEFENSE PLATFORM] ← Player builds here
            ║
═══════════════════════════════════════════════════════════
                   ATMOSPHERE
═══════════════════════════════════════════════════════════
                 PLANET SURFACE
                 [NEW BASTION]
    
    ┌────────────────────────────────┐
    │    ◇ CAPITAL (Must Protect)   │
    │                                │
    │  [SHIELD]  ▲  [SHIELD]        │
    │  GENERATOR │  GENERATOR        │
    │            │                   │
    │       [STARPORT]               │
    │       (Resource gathering)     │
    │                                │
    │  [BASE]        [BASE]          │
    │  WEST          EAST            │
    │                                │
    └────────────────────────────────┘
```

#### Base Building Layout
```
HUMAN BASE STRUCTURE:

         [COMMAND CENTER]
              ╔═══╗
              ║ ⚡ ║ ← Main building
              ╚═╦═╝
                ║
    ╔═══════════╬═══════════╗
    ║                       ║
[BARRACKS]              [FACTORY]
  ╔═══╗                   ╔═══╗
  ║🎖️ ║                   ║🏭║
  ╚═══╝                   ╚═══╝
  (Trains                 (Builds
  infantry)               vehicles)
    ║                       ║
    ╚═══════╦═══════════════╝
            ║
      [TECH LAB]
        ╔═══╗
        ║🔬║
        ╚═══╝
        (Research)
            ║
    ╔═══════╩═══════╗
[POWER]         [DEFENSE]
 ╔═══╗           ╔═══╗
 ║⚡║           ║🛡️║
 ╚═══╝           ╚═══╝
(Generator)    (Turrets)
```

#### Combat Flow - Wave Defense
```
WAVE 1 (Minute 0-5):
    Enemy: Light scouts
    ▼▼▼
    Player: Basic defenses
    ▲▲▲

WAVE 2 (Minute 5-10):
    Enemy: Frigates + Fighters
    ▼▼▼▼▼
    Player: Cruisers + Turrets
    ▲▲▲▲▲

WAVE 3 (Minute 10-15):
    Enemy: Capital ships + Elite
    ▼▼▼▼▼▼▼
    Player: Fleet + Titans
    ▲▲▲▲▲▲▲

BOSS WAVE (Minute 15-20):
    Enemy: Crystal Dreadnought
    ▼▼▼ BOSS ▼▼▼
    Player: All forces
    ▲▲▲▲▲▲▲▲▲▲
```

---

## Technical Implementation Notes

### Performance Targets

#### Siege of Rancor (RTS)
- **Frame Rate**: 60 FPS (minimum 30 FPS in large battles)
- **Unit Count**: Up to 500 units on screen
- **Draw Distance**: 5km for space battles
- **Resolution**: 1080p standard, 4K option

#### Shadow War (FPS)
- **Frame Rate**: 60 FPS (target on consoles)
- **Resolution**: Dynamic 1080p-4K
- **Player Count**: 12v12 in multiplayer
- **View Distance**: 1km with LOD

### Art Production Pipeline

#### 3D Asset Creation
```
WORKFLOW:
[Concept Art] →
[3D Blockout] →
[High-Poly Model] →
[Retopology] →
[UV Mapping] →
[Texture Creation] →
[Material Setup] →
[Rigging] →
[Animation] →
[Game Integration] →
[Optimization]
```

#### Texture Resolution Guidelines
- **Characters (Hero)**: 4K textures
- **Characters (NPC)**: 2K textures
- **Environments**: 2K-4K depending on prominence
- **Weapons (1st person)**: 4K
- **Weapons (3rd person)**: 2K
- **UI Elements**: Vector when possible, 1K-2K for icons

### Optimization Strategies

#### Level of Detail (LOD) System
```
LOD 0 (Close):    100% poly count
LOD 1 (Medium):    50% poly count
LOD 2 (Far):       25% poly count
LOD 3 (Very Far):  10% poly count (simplified silhouette)
```

#### Culling Techniques
- **Frustum Culling**: Don't render what camera can't see
- **Occlusion Culling**: Don't render objects blocked by others
- **Distance Culling**: Fade out distant small objects

---

## Style Guides

### Typography

#### In-Game Text
**Primary Font: "Aegis Gothic"** (custom font)
- Headers: Bold, 24pt-48pt
- Body: Regular, 12pt-16pt
- UI: Medium, 10pt-14pt

**Characteristics:**
- Industrial aesthetic
- High legibility at small sizes
- Slight angular design
- Includes special characters for alien text

#### Display Text
**Secondary Font: "Cathedral"** (decorative)
- Titles and logos only
- Gothic-inspired serifs
- Used sparingly for impact

### Icon Design Principles

**Rules:**
1. **Simple Silhouettes**: Recognizable at 32x32 pixels
2. **High Contrast**: Dark bg with light icons or vice versa
3. **Consistent Line Weight**: 2-3px stroke
4. **Unified Style**: All icons use same design language
5. **Color Coding**: 
   - Blue = Friendly/Ally
   - Red = Enemy/Danger
   - Yellow = Objective/Important
   - Green = Positive/Health

**Example Icon Set:**
```
UNIT ICONS:

[FIGHTER]    [CRUISER]    [TITAN]
   ╱╲           ▬▬▬         ║║
  ╱  ╲         ╱   ╲        ╠╣
 ◄────►       ◄═════►       ╠╣
  ╲  ╱         ╲   ╱        ╚╝
   ╲╱           ▬▬▬

ABILITY ICONS:

[ATTACK]    [DEFEND]    [REPAIR]    [SPECIAL]
   ⚔️          🛡️          🔧           ⚡
```

### Color Psychology

#### Human Aegis Fleet
**Blue** = Trust, Protection, Technology  
**Gold** = Prestige, Quality, Achievement  
**Gray** = Industrial, Practical, Sturdy

**Emotional Target:** Heroic, Steadfast, Reliable

#### Crystal Ravagers
**Purple** = Mystery, Power, Aristocracy  
**Blue** = Cold, Alien, Unknown  
**Black** = Menace, Sophistication, Void

**Emotional Target:** Eerie, Elegant, Threatening

---

## Animation & Motion

### Titan Movement Guidelines

**Walk Cycle:**
- Heavy footfalls with screen shake
- Slight lean forward when walking
- Arms sway slightly with momentum
- Each step creates dust/debris

**Combat Stance:**
- Weapon raised and ready
- Body angled for stability
- Constant micro-adjustments
- Breathing-like idle motion

### Pilot Parkour Animation

**Wall-Run:**
- Body tilts 45° toward wall
- Legs animate running motion
- Camera tilts slightly for feel
- Trail effect from boots

**Double Jump:**
- First jump: standard animation
- Mid-air moment: tuck position
- Second jump: boost burst from jump kit
- Landing: combat roll or slide

---

## Audio Design Notes

### Faction Sound Signatures

#### Human Weapons
- **Ballistic**: Loud, mechanical, echo
- **Impact**: Metallic clangs, explosions
- **Reloads**: Satisfying mechanical clicks

#### Crystal Weapons
- **Energy**: Hum, crystal chime, musical tones
- **Impact**: Shattering glass, crystalline ring
- **Ambience**: Constant low drone

### Environmental Audio

#### New Bastion City
**Layers:**
1. **Ambient**: Wind, distant traffic
2. **Mid**: Machinery, crowds, announcements
3. **Near**: Footsteps, conversations, details

**Dynamic:** Changes based on battle intensity

#### Crystal Ship Interior
**Layers:**
1. **Ambient**: Deep resonant hum
2. **Mid**: Crystal chimes, energy flow
3. **Near**: Footsteps echo, alien whispers

**Mood:** Unsettling, otherworldly

---

## Conclusion

This proof of concept document provides a comprehensive visual and design framework for the Evershade game series. All designs maintain the core gothic sci-fi aesthetic while ensuring gameplay clarity and visual distinctiveness between factions.

### Next Steps
1. **Prototype Key Assets**: Begin 3D modeling of hero characters and Titans
2. **UI Implementation**: Code functional versions of HUD designs
3. **Environment Tests**: Build one complete level section
4. **Playtesting**: Validate designs with player feedback
5. **Iteration**: Refine based on technical and gameplay needs

### Design Philosophy Summary
✓ Gothic meets Sci-Fi  
✓ Asymmetrical faction identity  
✓ Gameplay-first visual design  
✓ Atmospheric and immersive  
✓ Scalable across multiple games  

**End of Proof of Concept Overview**
