# Fire Pong 🏓🔥

A 2-player local arcade Pong clone built in Unity (C#) featuring dynamic ball velocity scaling, trajectory anti-lock physics, and fire particle effects.

🎮 **[Play the File Build on Itch.io] (https://yasani.itch.io/fire-pong)** 

---

## 🎮 Controls

Player - Move Up - Move Down 
 **Player 1 (Left)**  `W` && `S` 
 **Player 2 (Right)**  `Up Arrow` &&  `Down Arrow`

---

## ⚡ Key Mechanics & C# Architecture

* **Dynamic Speed Buildup:** Every paddle bounce incr.eases ball velocity.
* **Fire Mode State:** Crossing velocity thresholds dynamically triggers particle systems and audio loops.
* **Trajectory Anti-Lock:** Physics guard in `FixedUpdate` detects horizontal bounce traps and applies trajectory change.
* **Decoupled Logic:** Modular scripts handling ball physics, scoring triggers, and UI management.
* **Score Buildup:** An increasing score when ball shot in goal.
