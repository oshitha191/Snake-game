# Snake-game
A browser-based Snake Game built using HTML, CSS, and vanilla JavaScript with responsive keyboard controls, score tracking, and increasing difficulty. Implemented core game logic including snake movement, food generation, collision detection, and dynamic rendering using CSS Grid
# Project Flow

```mermaid
flowchart TD
    A[Start Game] --> B[Press Spacebar]
    B --> C[Initialize Snake & Food]
    C --> D[Start Game Loop]
    D --> E[Read Arrow Key Input]
    E --> F[Move Snake]
    F --> G{Collision?}

    G -- Yes --> H[Game Over]
    G -- No --> I{Food Eaten?}

    I -- Yes --> J[Increase Score]
    J --> K[Grow Snake]
    K --> L[Generate New Food]
    L --> M[Increase Speed]
    M --> D

    I -- No --> D
```
