# Diablo 4: Bosses

## Progression

```mermaid
flowchart TB

  WT12[World Tier 1 + 2]
  WT3[World Tier 3]
  WT4[World Tier 4]
  CD1[Capstone Dungeon 1]
  CD2[Capstone Dungeon 2]
  WS12[Whispers]
  WS3[Whispers]
  WS4[Whispers]
  HT3[Helltide]
  HT4[Helltide]
  WB12[World Bosses]
  WB3[World Bosses]
  WB4[World Bosses]
  LE12[Legion Events]
  LE3[Legion Events]
  LE4[Legion Events]
  NM3[Nighmare Dungeons Tiers 1-20]
  NM4[Nighmare Dungeons Tiers 21-100]
  EV3[Echo of Vershan]
  EV4[Echo of Vershan]
  DU4[Duriel, King of Maggots]
  GT3[Grigoire, The Galvanic Saint]
  GT4[Grigoire, The Galvanic Saint]
  LZ4[Lord Zir]
  BI4[The Beast in the Ice]
  EL[Echo of Lilith]

  CD1-->WT3
  CD2-->WT4
  WS12-->WS3
  WS3-->WS4
  LE12-->LE3
  LE3-->LE4
  WB12-->WB3
  WB3-->WB4

  subgraph 1-50
    WT12-->CD1
    WT12-->WB12
    WT12-->LE12
    WT12-->WS12
  end

  subgraph 51-70
    WT3-->CD2
    WT3-->NM3
    WT3-->WB3
    WT3-->LE3
    WT3-->WS3
    WT3-->HT3

    WS3-->EV3
    HT3-- 2 * Living Steel -->GT3
  end

  subgraph 71-100

    EB9[9 * Exquisite Blood]

    WT4-->WS4
    WT4-->NM4
    WT4-->HT4
    WT4-->WB4
    WT4-->LE4
    WT4-->EL

    HT4-- 5 * Living Steel -->GT4

    WB4-->EB9
    LE4-->EB9
    EB9-->LZ4

    WS4-->EV4
    WS4-->NM4

    NM4-- 9 * Distilled Fear -->BI4

    EV4-->DU4
    GT4-->DU4
  end
```

## Bosses and Items

### Template

- Barbarian
- Druid
- Necromancer
- Rogue
- Sorcerer
- All Classes
- Über Uniques

### Beast in Ice

- Barbarian
  - Fields of Crimson
  - 100000 Steps
  - Ancients' Oath
  - Battle Trance
  - Hellhammer
- Druid
  - Insatiable Fury
  - Hunter's Zenith
  - Waxing Gibbous
  - Storm's Companion
- Necromancer
  - Bloodless Scream
  - Howl from Below
  - Deathspeaker's Pendant
  - Ring of Mendeln
- Rogue
  - Condemnation
  - Word of Hakan
  - Windforce
  - Eaglehorn
- Sorcerer
  - Staff of Lam Esen
  - Esu's Heirloom
  - Gloves of the Illuminator
  - The Oculus
- All Classes
  - Frostburn
  - Mother's Embrace
  - Fists of Fate
  - Tassets of the Dawning Sky

### Duriel

- Barbarian
  - Azurewrath
  - Tuskhelm of Joritz the Mighty
- Druid
  - Dolmen Stone
  - Tempest Roar
- Necromancer
  - Black River
  - Blood Moon Breeches
- Rogue
  - Cowl of the Nameless
  - Scoundrel's Leathers
- Sorcerer
  - Blue Rose
  - Flamescar
- All Classes
  - Banished Lord's Talisman
  - Flickerstep
  - Godslayer Crown
  - Soulbrand
  - Tibault's Will
  - X'Fal's Corrodet Signet
- Über Uniques
  - Ahavarion, Spear of Lycander (Druid, Sorcerer)
  - Andariel's Visage
  - Doombringer (Barb, Necro, Rogue)
  - Harlequin Crest
  - Melted Heart of Selig
  - Ring of Starless Skies
  - The Grandfather (Barb, Necro)

### Grigiore

- Barbarian
  - Ramaladni's Magnum Opus
  - Rage of Harrogath
  - Ancients' Oath
  - Battle Trance
  - The Butcher's Cleaver
- Druid
  - Insatiable Fury
  - Hunter's Zenith
  - Waxing Gibbous
  - The Butcher's Cleaver
- Necromancer
  - Blood Artisan's Cuirass
  - Howl from Below
  - Greaves of the Empty Tomb
- Rogue
  - Word of Hakan
  - Grasp of Shadow
  - Windforce
- Sorcerer
  - Staff of Lam Esen
  - Iceheart Brais
  - Gloves of the Illuminator
- All Classes
  - Penitent Greaves

### Lord Zir

- Barbarian
  - Ramaladni's Magnum Opus
  - Rage of Harrohatg
  - Gohr's Devasting Grips
  - Overkill
  - The Butcher's Cleaver
- Druid
  - Mad Wolf's Glee
  - Vasily's Prayer
  - Greatstaff of the Crone
  - Fleshrender
  - The Butcher's Cleaver
- Necromancer
  - Blood Artisan's Cuirass
  - Deathless Visage
  - Greaves of the Empty Tomb
  - Lidless Wall
- Rogue
  - Grasp of Shadow
  - Eyses in the Dark
  - Skyhunter
  - Asheara's Khanjar
- Sorcerer
  - Staff of Endless Rage
  - Icehear Brais
  - Raiment of the Infinite
  - Esadora's Overflowing Cameo
- All Classes
  - Penitent Greaves
  - Razorplate
  - Temerity

### Varshan

- Barbarian
  - 100000 Steps
  - Fields of Crimson
  - Gohr's Devasting Grips
- Druid
  - Greatstaff of the Crone
  - Mad Wolf's Glee
  - Vasily's Prayer
- Necromancer
  - Bloodless Scream
  - Deathless Visage
  - Deathspeaker's Pendant
- Rogue
  - Condemnation
  - Eyes in the Dark
  - Skyhunter
- Sorcerer
  - Esu's Heirloom
  - Raiment of the Infinite
  - Staff of Endless Rage
- All Classes
  - Frostburn
  - Mother's Embrace
