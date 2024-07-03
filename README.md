# Battlespace 1.0.1

## Overview
Battlespace 1.0.1 is a space shooting game developed using the Java LibGDX framework. In this game, the player controls a spaceship and battles enemy ships while navigating through space. The player has three lives to progress through the game.

## Features
- **User Control**: Players can control their spaceship using keyboard inputs.
- **Enemy Ships**: Various enemy ships appear in waves, each with different behaviors and attack patterns.
- **Lives System**: The player starts with three lives—each collision with an enemy ship or projectile results in losing one life.
- **Score System**: Players can earn points by destroying enemy ships.

## Installation
1. **Clone the Repository**
    ```sh
    git clone https://github.com/yourusername/battlespace1.0.1.git
    cd battlespace1.0.1
    ```
2. **Import the Project into Your IDE**
    - Open your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).
    - Import the project as a Gradle project.

3. **Build the Project**
    - Ensure you have Gradle installed.
    - Run the following command to build the project:
    ```sh
    ./gradlew build
    ```

4. **Run the Game**
    - Execute the main class to start the game:
    ```sh
    ./gradlew run
    ```

## Controls
- **Arrow Keys**: Move the spaceship up, down, left, or right.
- **Space Bar**: Fire the spaceship's weapons.
- **Esc**: Pause/Unpause the game.

## Game Mechanics
- **Lives**: The player has three lives at the start of the game. Colliding with enemy ships or their projectiles reduces the player's lives.
- **Enemy Waves**: Enemy ships appear in waves, increasing in difficulty as the game progresses.
- **Scoring**: Destroy enemy ships to earn points. The score is displayed on the screen.

## Development
### Prerequisites
- Java 8 or higher
- LibGDX Framework
- Gradle

### Setting Up the Development Environment
1. **Install Java**: Ensure Java is installed on your system. You can download it from [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
2. **Install Gradle**: Follow the instructions [here](https://gradle.org/install/) to install Gradle.
3. **LibGDX Setup**: Follow the setup guide [here](https://libgdx.com/dev/setup/) to configure LibGDX.

### Folder Structure
- `src/main/java`: Contains the Java source files.
- `src/main/resources`: Contains the game assets (images, sounds, etc.).
- `build.gradle`: The Gradle build file.
- `README.md`: Project documentation.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or feedback, please reach out to [your email address].

Enjoy playing Battlespace 1.0.1!
