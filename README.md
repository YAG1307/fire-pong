# Fire Pong 🏓🔥

A 2-player local arcade Pong clone built in Unity (C#) featuring dynamic ball velocity scaling, trajectory anti-lock physics, and fire particle effects.

🎮 **[Play the WebGL Build on Itch.io]**

---

## 🎮 Controls

| Player | Move Up | Move Down |
| **Player 1 (Left)** | `W` | `S` |
| **Player 2 (Right)** | `Up Arrow` | `Down Arrow` |

---

## ⚡ Key Mechanics & C# Architecture

* **Dynamic Speed Buildup:** Every paddle bounce increments ball velocity to scale match intensity.
* **Fire Mode State:** Crossing velocity thresholds dynamically triggers particle systems and audio loops.
* **Trajectory Anti-Lock:** Physics guard in `FixedUpdate` detects horizontal loop traps and applies vertical variation.
* **Decoupled Logic:** Modular scripts handling ball physics, scoring triggers, and UI management.
* **Score Buildup:** An icnreasing score when ball shot in goal.
