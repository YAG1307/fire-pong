# Fire Pong 🔥

A 2-player local arcade Pong clone built in Unity (C#) featuring ball speed increase, anti-lock y-axis, and fire particle effects.

 **[Play the File Build on Itch.io] (https://yasani.itch.io/fire-pong)** 

---

# Controls

Move Paddle Up or Move Paddle Down
 Player 1 (Left):  W & S 
 Player 2 (Right):  Up Arrow & Down Arrow

---

## Summary of Code

* Dynamic Speed Buildup: Every paddle bounce increases ball velocity.
* Fire Mode State: When ball reaches certain speed, the ball has special fire particles and sound effects as well as increased speed.
* Y-Axis Anti-Lock: Event called in FixedUpdate detects horizontal bounce traps and applies trajectory change.
* **Score Buildup:** An increasing score when ball shot in goal. 
