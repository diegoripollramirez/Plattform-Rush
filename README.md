# Plattform Rush

**Plattform Rush** is a thrilling platformer game where players navigate through challenging levels, collect coins, defeat enemies, and purchase upgrades to enhance their abilities.  
Developed using **C#** in **Unity**, the game offers a fun, fast-paced experience with the goal of becoming the most powerful character in the game world.

## Features

- **Collect Coins**: Gather coins throughout each level to use for upgrades.
- **Defeat Enemies**: Crush enemies to clear your path and gain rewards.
- **Upgrade System**: Enhance your character's abilities with various upgrades.
- **Procedurally Generated Levels**: Levels are dynamically generated using procedural generation techniques.
- **Persistent Data**: Player data is stored in a **MySQL** database, ensuring progress is saved between sessions.

## Tech Stack

- **Frontend**: Unity (C#)
- **Backend**: Java (Sockets)
- **Database**: MySQL

## Installation

### 2. Install Dependencies

- **Unity**: Make sure you have Unity installed (Version X.X or later).
- **JDK**: Install Java Development Kit (JDK) version X.X or later.
- **MySQL**: Ensure that MySQL is installed and running to store player data.
- **.NET Framework**: Required for C# development (if needed).

### 3. Set Up the Database

- Ensure that **MySQL** is configured correctly. 
- Set up the necessary tables in the database for storing player data and progress.
- Check the backend configuration for database connection details and credentials.

### 4. Run the Backend Server

- Navigate to the server directory where the backend code is located.
- Run the server:

  ```bash
  cd server
  java -jar server.jar
 
### 5. Run the Game

- Open the project in **Unity**.
- Hit **Play** to start the game in the Unity editor.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.
