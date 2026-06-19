# Quantum Backrooms: The Observer’s Maze

[![Play Online](https://img.shields.io/badge/Play%20Online-quantum--backrooms.vercel.app-00cc88?style=for-the-badge&logo=vercel)](https://quantum-backrooms.vercel.app/)
[![Repository](https://img.shields.io/badge/GitHub-Quantum--Backrooms--Maze-181717?style=for-the-badge&logo=github)](https://github.com/lakshyabuilds/Quantum-Backrooms-Maze/)
[![Three.js](https://img.shields.io/badge/Three.js-WebGL%20Horror-ffffff?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![Made by Techiral](https://img.shields.io/badge/Created%20by-Techiral%20%28Lakshya%20Gupta%29-8b5cf6?style=for-the-badge)](https://github.com/lakshyabuilds)

![Quantum Backrooms Hero](https://github.com/lakshyabuilds/Quantum-Backrooms-Maze/blob/main/quantum-backrooms.jpg?raw=true)

> **A reality-bending browser horror game where observation changes the maze.**  
> Walls shift when ignored. Quantum walls collapse and reconfigure. Entangled passages echo your actions. Shadow entities stalk the grid. The only stable path is the one you can survive long enough to discover.

---

## Overview

**Quantum Backrooms: The Observer’s Maze** is a first-person, browser-playable horror maze built with **Three.js** and designed around a quantum-inspired gameplay loop: look at the maze, and it stabilizes; look away, and reality starts to fail.

The game is built as a surreal escape experience with:
- procedural maze generation,
- quantum wall states,
- entangled wall behavior,
- interactive key-and-exit progression,
- stalking entities,
- traps,
- hallucination events,
- jump-scare pressure,
- level-based escalation.

Play it here: [https://quantum-backrooms.vercel.app/](https://quantum-backrooms.vercel.app/)

Source repository: [https://github.com/lakshyabuilds/Quantum-Backrooms-Maze/](https://github.com/lakshyabuilds/Quantum-Backrooms-Maze/)

---

## What this game is

This project is not a generic maze clone. It is a **quantum horror simulation** with a strong visual identity and a distinct mechanical thesis:

> **Observation is control. Neglect is danger.**

The maze reacts to the player’s viewpoint, movement, and timing. That makes every decision both navigational and psychological.

---

## Core Experience

### The loop
1. Enter the maze.
2. Find the key.
3. Reach the exit.
4. Survive entities, traps, and quantum instability.
5. Escalate into higher levels with larger and more unstable mazes.

### What creates tension
- walls that can shift or collapse when not observed,
- quantum tunneling that can phase the player through blocked paths,
- entities that freeze when watched and become dangerous when ignored,
- trap zones that relocate the player,
- ambient audio and glitch effects,
- visual instability that increases with progression.

---

## Key Features

- **Procedural maze generation**
- **Quantum wall states**: solid, open, quantum, and critical paths
- **Observer effect gameplay**
- **Entangled wall pairs**
- **First-person movement with pointer lock**
- **Sprint and interaction mechanics**
- **Key-and-exit level progression**
- **Shadow entities with state-based behavior**
- **Quantum traps**
- **Hallucinations and audio glitches**
- **Jump-scare events**
- **Progressive difficulty across levels**
- **Immersive visual post-processing**
- **Cinematic horror presentation in-browser**

---

## For Players

### What you do
- Use **WASD** to move.
- Use the mouse to look around.
- Press **F** to interact.
- Hold **Shift** to sprint.
- Find the **key**.
- Reach the **exit**.
- Repeat across increasingly unstable levels.

### What to expect
- The maze becomes larger and more hostile over time.
- Looking at threats can keep them frozen.
- Ignoring them can cause aggressive behavior.
- Quantum walls can become unstable and change state.
- The atmosphere is deliberately oppressive.

---

## Game Mechanics

### Observation-driven walls
Certain walls are marked as **quantum**. These can fluctuate over time when they are not being observed. That creates an unstable navigation layer where the map is never fully trusted.

### Critical paths
The maze preserves a guaranteed route from start to key and from key to exit. That means the game remains solvable while still feeling unpredictable.

### Quantum tunneling
If the player collides with a wall and the tunneling system activates, movement can phase through the obstacle. This is not random decoration. It is a core mechanic tied to instability and level pressure.

### Entangled walls
Some quantum walls are paired. Changing one can trigger a change in its partner, creating cause-and-effect behavior that makes the maze feel physically connected.

### Entities
Shadow entities:
- freeze when watched,
- stalk when unobserved,
- become aggressive under sustained pressure,
- can trigger jump scares,
- increase instability when they hit the player.

### Traps
Quantum traps:
- detect nearby movement,
- trigger after sustained contact,
- relocate the player,
- create audio and visual disturbances.

### Hallucinations
The game periodically injects:
- fog color shifts,
- chromatic drift,
- audio glitches,
- misleading audio cues,
- visual noise and distortion.

---

## Controls

| Action | Key |
|---|---|
| Move forward | `W` / `Arrow Up` |
| Move backward | `S` / `Arrow Down` |
| Move left | `A` / `Arrow Left` |
| Move right | `D` / `Arrow Right` |
| Interact | `F` |
| Sprint | `Shift` |
| Look around | Mouse |
| Focus / pointer lock | Click the game |

---

## Audience Modes

## For Gamers

### The pitch
This is the kind of game people open “just to test it” and end up staying in for the atmosphere. It is built to feel like a **suspense-driven launch title teaser**: bold title, striking visuals, heavy identity, and a mechanic hook that is immediately understandable.

### Why it hits
- immediate first-person immersion,
- strong horror branding,
- escalating danger,
- unpredictable maze changes,
- collectible objective structure,
- a clear win condition,
- enough tension to keep every room meaningful.

### Player fantasy
You are not just escaping a maze. You are trying to outthink a hostile reality system while being watched by things that should not exist.

---

## For Researchers / Scientists

### Abstract
This project models a perceptual horror environment in which spatial stability depends on player observation. The result is a deterministic-but-unstable maze system combining procedural generation, conditional state transitions, entangled event propagation, and sensory disruption.

### Research-style framing
**Hypothesis:** If maze geometry reacts to player attention, then navigational certainty decreases while perceived agency increases.

**Observed phenomena:**
- wall-state mutation under non-observation,
- entangled propagation between paired quantum walls,
- stochastic entity escalation,
- trap-based displacement,
- adaptive instability with level progression.

**Interpretation:**  
The game creates a feedback loop between player attention and environmental entropy. The maze is therefore not only a level space, but a behavioral system.

### Technical implications
This structure is useful for:
- horror game systems design,
- procedural level design,
- attention-based mechanics,
- simulation of unstable environments,
- audio-visual state coupling,
- stateful browser-based 3D gameplay.

---

## For Developers

### Name
`quantum-backrooms`

### Purpose
Browser-based first-person horror maze with quantum-inspired environmental instability.

### Runtime profile
- Runs in the browser
- Uses **Three.js**
- Uses **WebGL rendering**
- Uses **pointer lock** for first-person navigation
- Uses **Web Audio** for psychoacoustic horror effects

### Primary subsystems
- `maze generation`
- `wall state engine`
- `entity AI`
- `trap logic`
- `audio engine`
- `hallucination system`
- `level progression`
- `UI overlay system`

### Operational behavior
- Maze is generated per level.
- Key and exit are placed each round.
- A guaranteed critical route is preserved.
- Quantum walls can mutate when unobserved.
- Interaction can toggle nearby quantum walls.
- Entities use look-based state transitions.
- Traps can relocate the player.
- Instability increases visual and audio pressure.

### Failure modes
- pointer lock can be lost,
- the game can appear hostile by design,
- the player may be displaced by traps or tunneling,
- auditory effects may intensify as instability increases.

### Assumptions
- Desktop browser provides the best experience.
- Mouse input is central.
- Audio access is part of the intended experience.

---

## Why This Project Stands Out

### 1. It has a real mechanic thesis
The concept is not only visual. It is systemic: **observation affects reality**.

### 2. It has strong theme consistency
Every layer supports the same idea:
- title,
- copy,
- maze behavior,
- sound design,
- visual treatment,
- UI text.

### 3. It is built for shareability
The premise is easy to describe:
> “A horror maze where walls change when you look away.”

That is exactly the kind of sentence people repeat.

### 4. It works as a portfolio piece
It demonstrates:
- WebGL scene construction,
- procedural logic,
- game-state design,
- input handling,
- atmospheric UI,
- interaction design,
- brand-level presentation.

---

## SEO / AEO Section

### Primary search intent
- quantum horror game
- backrooms browser game
- Three.js maze game
- free online horror game
- psychological maze game
- quantum tunneling game
- observer effect game
- browser-based 3D horror experience

### High-value semantic keywords
quantum backrooms, observer’s maze, quantum maze, horror maze, browser horror, WebGL horror, Three.js game, psychological horror, quantum tunneling, quantum entanglement, shadow entities, jumpscare maze, escape room horror, surreal horror, free online game, Lakshya Gupta, Techiral

### Answer Engine Optimization summary
**What is Quantum Backrooms?**  
A browser-based horror maze where observation and quantum instability shape the environment.

**How do you win?**  
Find the key, reach the exit, and survive the escalating maze across levels.

**What makes it unique?**  
Walls can fluctuate, quantum paths can change, entities react to your gaze, and the maze becomes more unstable over time.

**Who built it?**  
Techiral, by Lakshya Gupta.

---

## Technical Stack

- **Three.js**
- **WebGL**
- **HTML**
- **CSS**
- **JavaScript**
- **Web Audio API**
- **Pointer Lock API**
- **Procedural generation**
- **State-driven game logic**

---

## Visual Identity

The presentation uses a deliberately oppressive palette and interface style:
- dark background,
- warm desaturated maze materials,
- vignette and chromatic drift,
- glitch flashes,
- minimal in-world HUD,
- cinematic title treatment,
- retro-terminal visual language.

This keeps the game feeling like an artifact rather than a generic web app.

---

## Branding

**Created by Techiral (Lakshya Gupta).**

This project supports the broader Techiral identity: experimental, systems-driven, attention-heavy interactive design with strong visual branding and high memorability.

For more work and project context:
- GitHub: [lakshyabuilds](https://github.com/lakshyabuilds)
- Live game: [quantum-backrooms.vercel.app](https://quantum-backrooms.vercel.app/)

---

## FAQ

### Is this a standard maze game?
No. It is an attention-reactive horror maze with quantum-flavored instability.

### Is it playable in the browser?
Yes. The game is hosted online and runs in-browser.

### Does the maze stay static?
No. Some walls can fluctuate or alter state based on observation and game logic.

### Is there a win condition?
Yes. Find the key, reach the exit, and clear levels.

### Is the project intended as a portfolio piece?
Yes. It is also a branded technical and creative showcase.

---

## Final Line

**Quantum Backrooms: The Observer’s Maze** is designed to feel like a haunted system that understands when it is being watched.
