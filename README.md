
<!-- CHUNK 1 START -->

<!-- 
  SEO KEYWORDS: JavaFX Racing Game, Java 21 Game Development, OOP Design Patterns, 
  Open Source Car Game, Maven Project Structure, 2D Survival Racer
-->

<div align="center">
 
  <!-- HERO BANNER: Dynamic Capsule Render with Gradient -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,35,40,45&height=300&section=header&text=Racing%20Game&fontSize=90&animation=fadeIn&fontAlignY=38&desc=high-Octane%20JavaFX%20Survival%20Racer&descAlign=62" alt="Racing Game JavaFX Hero Banner" width="100%" />

  <!-- ANIMATED SUBTITLE: Typing SVG for Value Propositions -->
  <a href="https://github.com/amir-hossein-khodaei/javafx-racing-game">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=3388FF&center=true&vCenter=true&width=435&lines=Object-Oriented+Design+Showcase;JavaFX+21+GUI+Architecture;High-Speed+Survival+Action;Maven-Built+Open+Source+Project" alt="Typing Animation: OOP Design, JavaFX GUI, Survival Action" />
  </a>

  <!-- BADGES: High-Value Metadata -->
  <p>
    <a href="https://github.com/amir-hossein-khodaei/javafx-racing-game/graphs/contributors">
      <img src="https://img.shields.io/github/contributors/amir-hossein-khodaei/javafx-racing-game?style=for-the-badge&color=2ecc71" alt="Contributors" />
    </a>
    <a href="https://github.com/amir-hossein-khodaei/javafx-racing-game/network/members">
      <img src="https://img.shields.io/github/forks/amir-hossein-khodaei/javafx-racing-game?style=for-the-badge&color=e67e22" alt="Forks" />
    </a>
    <a href="https://github.com/amir-hossein-khodaei/javafx-racing-game/stargazers">
      <img src="https://img.shields.io/github/stars/amir-hossein-khodaei/javafx-racing-game?style=for-the-badge&color=f1c40f" alt="Stargazers" />
    </a>
    <a href="https://github.com/amir-hossein-khodaei/javafx-racing-game/issues">
      <img src="https://img.shields.io/github/issues/amir-hossein-khodaei/javafx-racing-game?style=for-the-badge&color=e74c3c" alt="Open Issues" />
    </a>
    <a href="https://github.com/amir-hossein-khodaei/javafx-racing-game/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/amir-hossein-khodaei/javafx-racing-game?style=for-the-badge&color=3498db" alt="MIT License" />
    </a>
  </p>

  <br />

  <!-- ACTION BUTTONS -->
  <p>
    <a href="#getting-started">
      <img src="https://img.shields.io/badge/Get_Started-000000?style=flat-square&logo=speedtest&logoColor=white" alt="Get Started Button" height="35" />
    </a>
    &nbsp;
    <a href="https://github.com/amir-hossein-khodaei/javafx-racing-game/releases">
      <img src="https://img.shields.io/badge/Download_Latest-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Download Release Button" height="35" />
    </a>
  </p>
</div>

<br />

---

## 📋 Table of Contents

<details>
<summary>Click to expand</summary>

1. [About The Project](#-about-the-project)
    - [Key Features](#key-features)
    - [Built With](#built-with)
2. [Demo & Visuals](#-demo--visuals)
    - [Screenshots](#screenshots)
    - [Architecture](#architecture)
3. [Getting Started](#-getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
4. [Usage](#-usage)
    - [Controls](#controls)
    - [Game Mechanics](#game-mechanics)
5. [Roadmap](#-roadmap)
6. [Contributing](#-contributing)
7. [License](#-license)
8. [Contact & Acknowledgments](#-contact--acknowledgments)

</details>

---

## 🏎️ About The Project

**Racing Game** (internal codename `GTA_VI`) is a high-speed, vertical-scrolling survival racer built entirely in **Java 21** and **JavaFX**. Designed as a comprehensive showcase of **Object-Oriented Programming (OOP)** principles, this project demonstrates how to architect a real-time game loop, manage complex entity states, and handle collision detection without relying on heavy game engines like Unity or Godot.

In this adrenaline-fueled chase, players take the wheel of a high-performance vehicle on a relentless highway. The mission is simple but deadly: survive as long as possible while dodging military convoys, evading terrorist bombers, and managing critical resources like fuel and vehicle integrity.

### Key Features

*   **Advanced OOP Architecture**: Clean separation of concerns using inheritance and polymorphism for entity management (`SoldierCar`, `TerroristCar`, `NormalCar` all extending `ScreenObject`).
*   **Dynamic Enemy AI**: three distinct enemy classes with unique behaviors—some block your path, while others actively fire projectiles or drop explosives.
*   **Resource Management System**: Strategic gameplay requiring players to balance speed with fuel consumption (`Gas`) and hull integrity (`Heart`).
*   **Persisted High Scores**: A custom flat-file database system that tracks player performance, login timestamps, and historical run data across sessions.
*   **Modular UI**: Built with JavaFX FXML for a separation of layout and logic, featuring animated menus, rainy weather effects, and responsive HUDs.

### Built With

This project leverages a modern Java ecosystem to deliver a performant desktop experience:

| Tech | Badge | Description |
|:---:|:---|:---|
| **Language** | ![Java 21](https://img.shields.io/badge/Java_21-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) | Core logic and game loop execution. |
| **Framework** | ![JavaFX](https://img.shields.io/badge/JavaFX-007396?style=for-the-badge&logo=java&logoColor=white) | Hardware-accelerated GUI toolkit for rendering. |
| **Build Tool** | ![Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white) | Dependency management and build lifecycle. |
| **UI Libs** | ![ControlsFX](https://img.shields.io/badge/ControlsFX-11.1.2-blue?style=for-the-badge) | Enhanced UI controls and dialogs. |
| **Format** | ![FXML](https://img.shields.io/badge/FXML-XML_UI-orange?style=for-the-badge) | XML-based user interface markup. |































<!-- CHUNK 2 START -->

## 🎥 Demo & Visuals

Experience the intense action of the Racing Game. The interface features dynamic weather effects (rain), animated enemy sprites, and a real-time HUD.

### Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="menu.png" alt="Main Menu Screen with Start Options" width="400" />
        <br />
        <em>Main Menu & Player Selection</em>
      </td>
      <td align="center">
        <img src="game1.png" alt="Gameplay Action Screenshot - Highway Chase" width="400" />
        <br />
        <em>High-Speed Highway Pursuit</em>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="game2.png" alt="Gameplay Action Screenshot - Combat" width="400" />
        <br />
        <em>Combat & Obstacle Evasion</em>
      </td>
      <td align="center">
        <img src="scores.png" alt="High Score Table Leaderboard" width="400" />
        <br />
        <em>Persistent Leaderboards</em>
      </td>
    </tr>
  </table>
</div>

### Architecture

The game is built on a robust **Object-Oriented** foundation. All moving entities inherit from a central `ScreenObject` class, ensuring consistent rendering and collision logic.

```mermaid
classDiagram
    class ScreenObject {
        +double x
        +double y
        +Image img
        +addToPane()
        +garbageCollect()
    }
    class PlayerCar {
        +shoot()
        +moveLeft()
        +moveRight()
    }
    class EnemyEntity {
        <<Abstract>>
        +attack()
    }
    class SoldierCar {
        +fireProjectiles()
    }
    class TerroristCar {
        +dropBombs()
    }
    class GameLoop {
        +checkCollisions()
        +updatePhysics()
    }

    ScreenObject <|-- PlayerCar
    ScreenObject <|-- EnemyEntity
    ScreenObject <|-- PowerUp
    EnemyEntity <|-- SoldierCar
    EnemyEntity <|-- TerroristCar
    GameLoop ..> ScreenObject : Manages
```

---

## 🚀 Getting Started

Follow these steps to get a local copy up and running. This project is built with **Maven**, ensuring dependency management is automated.

### Prerequisites

*   **Java Development Kit (JDK) 21** or higher.
    *   *Verify with:* `java -version`
*   **Git** (to clone the repository).
*   **Maven** (optional, as the project includes a wrapper).

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/amir-hossein-khodaei/javafx-racing-game.git
    cd javafx-racing-game
    ```

2.  **Initialize the Wrapper & Build**
    Use the included Maven Wrapper (`mvnw`) to ensure the correct Maven version is used.
    
    *   **Windows:**
        ```powershell
        ./mvnw.cmd clean install
        ```
    *   **Mac/Linux:**
        ```bash
        chmod +x mvnw
        ./mvnw clean install
        ```

3.  **Run the Game**
    Launch the application directly via the JavaFX Maven plugin:
    ```bash
    # Windows
    ./mvnw.cmd javafx:run

    # Mac/Linux
    ./mvnw javafx:run
    ```

---

## 🎮 Usage

Once the game launches, you will be prompted to **Sign Up** or **Log In**. The game saves your progress locally in `.txt` files, tracking your high scores across sessions.

### Controls

| Action | Key / Input | Description |
| :--- | :---: | :--- |
| **Steer Left** | <kbd>A</kbd> | Move vehicle to the left lane. |
| **Steer Right** | <kbd>D</kbd> | Move vehicle to the right lane. |
| **Fire Weapon** | <kbd>Left Click</kbd> | Shoot projectiles at enemies ahead. |
| **Menu Nav** | <kbd>Mouse</kbd> | Click to select options in menus. |

### Game Mechanics

Your survival depends on managing three core resources displayed on the HUD:

1.  **❤️ Health (Heart Bar)**: Depletes when you collide with enemies or get hit by enemy fire.
    *   *Recover:* Collect **Heart** power-ups.
    *   *Critical:* Hitting 0 ends the run.

2.  **⛽ Fuel (Gas Bar)**: Constantly drains as you drive.
    *   *Recover:* Collect **Gas Can** items.
    *   *Critical:* Running out of fuel stops the car and ends the game.

3.  **🛡️ Power-Ups**:
    *   **Shield**: Temporary invincibility.
    *   **Speed Boost**: Short burst of acceleration (increases score multiplier).
    *   **Ammo**: Replenishes projectile count for your weapon.


































<!-- CHUNK 3 START -->

## 🗺️ Roadmap

- [x] **Core Mechanics**: Collision detection, shooting, and enemy spawning.
- [x] **Persistence**: Player profiles and high-score saving via local storage.
- [x] **Visuals**: Dynamic weather (rain), animated sprites, and scrolling backgrounds.
- [ ] **Sound Settings**: Add volume sliders for SFX and Music in the pause menu.
- [ ] **Executable Packaging**: Bundle with `jpackage` for a standalone `.exe` or `.dmg`.
- [ ] **Refactoring**: Migrate from flat-file storage to SQLite for robust data management.

See the [open issues](https://github.com/amir-hossein-khodaei/javafx-racing-game/issues) for a full list of proposed features (and known issues).

---

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  **Fork the Project**
2.  **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3.  **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4.  **Push to the Branch** (`git push origin feature/AmazingFeature`)
5.  **Open a Pull Request**

### Top Contribution Ideas
*   *Asset Swap*: Replace placeholder sprites with custom pixel art.
*   *New Enemies*: Create a new class extending `EnemyEntity`.
*   *Optimization*: Improve the garbage collection logic in `ScreenObject`.

---

## 📝 License

Distributed under the **MIT License**. See `LICENSE` for more information.

This project is open-source and free to use. You can copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software.

---

## 👏 Acknowledgments

This project wouldn't be possible without the inspiration and assets from the following sources:

*   **Gran Turismo**: For the iconic audio tracks that fuel the racing atmosphere.
*   **Must Deliver**: The primary inspiration for the vertical scrolling map design.
*   **Pinterest & Generative AI**: Various sprite assets and background textures.
*   **OpenJFX Community**: For the robust documentation on JavaFX modularity.


<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,35,40,45&height=100&section=footer" width="100%" alt="Footer Wave">
</div>