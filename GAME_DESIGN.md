# Duck Hunt AR - Game Design Document

## Current Version: v0.5

---

## Core Concept
Browser-based Duck Hunt clone with AR webcam integration. Player uses hand gestures (finger gun with thumb tuck trigger) to aim and shoot ducks on screen.

---

## Implemented Features

### Controls
- Index finger pointing = aim (crosshair follows)
- Thumb tuck = shoot (trigger pull gesture)
- Lerp-based smooth crosshair tracking

### Visuals
- NES Duck Hunt style background (blue sky, trees, grass, bushes)
- Pixel art ducks with wing flap animation
- Webcam preview in corner
- Mascot with speech bubble commentary
- Retro 8-bit UI styling

### Gameplay
- 10 ducks per round
- Score tracking
- Accuracy calculation
- End-of-round roast based on performance

---

## Shelved Ideas (Future Iterations)

### Duck Variety Pack
| Type | Behavior | Points | Notes |
|------|----------|--------|-------|
| Normal | Standard flight | 100 | Baseline |
| Drunk | Wobbles randomly, unpredictable path | 150 | Hard to predict |
| Dodger | Actively evades crosshair when aimed at | 250 | Moves away when you target it |
| Teleporter | Blinks to new position periodically | 400 | High value, high difficulty |
| Decoy | Spawns 2 fake copies, only real one counts | 300 | Mind games |
| Golden | Rare spawn, fast, high points | 500 | Jackpot duck |

### Competitive/Retention Features

#### Leaderboards
- Daily/weekly/all-time high scores
- Accuracy rankings
- Speed run mode rankings

#### Multiplayer
- **1v1 Duels**: Split screen, same ducks, who gets more
- **Co-op Wave Survival**: 2 players, shared screen, escalating difficulty
- **Spectator mode**: Watch top players live

#### Progression System
- XP and ranks
- Titles earned through achievements
- Unlockable content gated by progression

#### Daily Challenges
- "Get 10 headshots"
- "No misses for 30 seconds"
- "Kill 5 teleporters in one round"
- Rotating daily/weekly challenges

### Cosmetics & Unlockables

#### Gun/Crosshair Skins
- Neon glow
- Pixel retro
- Laser pointer
- Golden crosshair

#### Hand Effects
- Flame trail
- Electric sparks
- Rainbow trail
- Matrix green

#### AR Overlays
- Cyberpunk visor
- Contra-style scope
- Military HUD
- Anime power level scanner

#### Duck Variants (Visual)
- Zombie ducks (Halloween)
- Present boxes (Christmas)
- Golden ducks
- Robot ducks

### Gameplay Modifiers

#### Difficulty Modes
- **Easy**: Slow ducks, large hitbox
- **Normal**: Balanced
- **Hard**: Fast ducks, small hitbox
- **Nightmare**: Dodger behavior on all ducks

#### Challenge Modes
- **Moving Webcam**: Preview window moves around screen (your idea!)
- **Drunk Mode**: Webcam sways
- **Paranoia Mode**: Webcam shrinks over time
- **Strobe Mode**: Webcam flickers on/off
- **Mirror Mode**: Controls inverted
- **One Shot**: Miss once, game over

#### Round Modifiers
- Limited ammo (3 shots per duck)
- Time pressure per duck
- Escalating difficulty per round
- Boss ducks every 5 rounds

### Share Moments (Viral Features)

#### The Roast Card
Brutally honest end-of-round stats card:
- Accuracy roast
- Reaction time roast
- Shareable image format

#### Replay Kill Cam
- Best shot of the round
- Slow-mo dramatic angle
- Auto-generates 3-second clip
- One-tap share

#### Streak Titles
Hit streaks earn titles:
- 5x: "Warming Up"
- 10x: "The Problem"
- 15x: "Geneva Convention Violator"
- 20x: "Duck's Worst Nightmare"

Miss streaks earn shame titles:
- 5x: "Liability"
- 10x: "Duck Sympathizer"
- 15x: "Legally Blind"

#### The Receipt
End screen styled like brutal receipt:
```
DUCK HUNT RECEIPT
-----------------
Shots fired:     47
Shots hit:       12
Accuracy:        25%
Ducks escaped:   8
Dignity lost:    ALL

Rating: CERTIFIED MEAL
       (for the ducks)
```

### Sound Design
- Gunshot on fire
- Duck quacks (randomized)
- Splat/explosion on hit
- Womp womp on miss
- Wing flapping ambient
- Mascot voice lines (TTS or pre-recorded)
- Retro 8-bit soundtrack
- Combo sound effects (escalating pitch)

### Mascot Enhancements
- Visual animations (not just speech)
  - Laughing animation on miss
  - Shocked/impressed on combo
  - Smug idle animation
  - Pointing at ducks (taunt)
- Voice lines (audio)
- Different mascot skins/characters

### Monetization Options
- **Cosmetic packs**: Premium skins
- **Battle pass**: Weekly challenges, tiered rewards
- **Pro mode**: One-time unlock for ranked, custom lobbies, detailed stats
- **Supporter tier**: No ads, exclusive badge, name in credits
- Ad-supported free tier

### Technical Improvements
- Mobile support (touch controls)
- Gamepad support
- Better hand tracking in various lighting
- Performance optimization
- Offline mode

---

## Immediate Next Steps (v0.6)
1. Duck variety pack implementation
2. Sound effects
3. Escalating rounds
4. Limited ammo system
5. Moving webcam challenge mode

---

## Long-term Vision
A viral-ready AR shooting game that combines nostalgia with modern humor. The "prove the mascot wrong" dynamic is the core retention hook. Share moments are designed for social media virality.

---

*Last updated: v0.5*
