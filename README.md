A classic Asteroids-style arcade game implemented in Python using pygame.

**The game includes**:

A player-controlled spaceship

Rotation + forward/back movement

Shooting bullets with cooldown

Spawning asteroids of different sizes

Splitting large asteroids into smaller ones

Collision detection

Sprite groups for clean update/draw logic

**🚀 Features**
_✔ Player Movement_

Rotate left/right (A / D)

Move forward/backward (W / S)

Smooth delta-time based movement

_✔ Shooting_

Press SPACE to shoot bullets

Bullets move forward at high speed

Shot cooldown: 0.3 seconds

_✔ Asteroids_

Spawn from edges at random intervals

Move in straight lines with random angles

Different sizes (large → medium → small)

Split when shot

Kill the player on collision

_✔ Collision Handling_

Shot hits asteroid → asteroid splits

Player hits asteroid → game over

_✔ Clean Architecture_

**Classes:**

CircleShape

Player

Asteroid

AsteroidField

Shot

**Uses sprite groups**:

updatable

drawable

asteroids

shots

📁 Project Structure
klonov/
│
├── asteroid.py
├── asteroidfield.py
├── circleshape.py
├── constants.py
├── logger.py
├── main.py
├── player.py
├── shot.py
├── README.md
└── .gitignore

**🛠 Technologies Used**

Python 3

Pygame

Boot.dev project architecture
