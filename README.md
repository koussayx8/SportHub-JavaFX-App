# 🏆 SportHub - JavaFX Application

[![Java Version](https://img.shields.io/badge/Java-11%2B-orange)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
[![JavaFX](https://img.shields.io/badge/JavaFX-15%2B-blue)](https://openjfx.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

<p align="center">
  <img src="docs/images/sporthub_logo.png" alt="SportHub Logo" width="300"/>
</p>

## 📝 Overview

SportHub is a comprehensive JavaFX desktop application designed to manage and track sports events, teams, players, and statistics. With an intuitive user interface and powerful backend, SportHub offers a complete solution for sports enthusiasts, team managers, and event organizers.

## ✨ Features

- **User Authentication** - Secure login and registration system
- **Dashboard** - At-a-glance view of important statistics and upcoming events
- **Team Management** - Add, edit, and organize teams with detailed profiles
- **Player Profiles** - Comprehensive player information and performance metrics
- **Event Scheduling** - Create and manage sports events with calendar integration
- **Statistics Tracking** - Real-time updates and historical data visualization
- **Customizable Reports** - Generate PDF and Excel reports for teams and events
- **Multi-sport Support** - Configurable for various sports disciplines

## 🖼️ Screenshots

<div align="center">
  <img src="docs/images/screenshot1.png" alt="Dashboard" width="400"/>
  <img src="docs/images/screenshot2.png" alt="Team Management" width="400"/>
</div>

## 🛠️ Technologies

- **JavaFX** - For building the desktop application UI
- **Java** - Core programming language
- **FXML** - For UI layout design
- **CSS** - For UI styling
- **SQLite/MySQL** - Database backend options
- **Maven/Gradle** - Dependency management and build automation
- **JUnit** - For unit testing
- **FontAwesomeFX** - For icons and visual elements
- **JFoenix** - Material design components

## 📋 Prerequisites

- Java 11 or higher
- JavaFX SDK 15 or higher
- Maven or Gradle
- Database (SQLite or MySQL)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/koussayx8/SportHub-JavaFX-App.git
   cd SportHub-JavaFX-App
   ```

2. **Setup the database**
   - Create a database using the provided schema in `database/schema.sql`
   - Configure the connection in `src/main/resources/config.properties`

3. **Build the project**
   ```bash
   mvn clean install
   ```

4. **Run the application**
   ```bash
   mvn javafx:run
   ```

## 💻 Usage

After launching the application:

1. **Login** with your credentials or register a new account
2. **Navigate** through the sidebar to access different features
3. **Manage teams** by adding players, scheduling matches, and tracking performance
4. **Generate reports** on team performance and upcoming events
5. **Customize settings** according to your preferences

## 📊 Class Diagram

<p align="center">
  <img src="docs/images/class_diagram.png" alt="Class Diagram" width="600"/>
</p>

## 📁 Project Structure

```
SportHub-JavaFX-App/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com/sporthub/
│   │   │   │   ├── controllers/
│   │   │   │   ├── models/
│   │   │   │   ├── services/
│   │   │   │   ├── utils/
│   │   │   │   └── Main.java
│   │   ├── resources/
│   │   │   ├── fxml/
│   │   │   ├── css/
│   │   │   ├── images/
│   │   │   └── config.properties
│   ├── test/
│       └── java/
├── database/
├── docs/
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- [JavaFX Documentation](https://openjfx.io/)
- [JFoenix Library](https://github.com/jfoenixadmin/JFoenix)
- [FontAwesomeFX](https://bitbucket.org/Jerady/fontawesomefx)
- All contributors and testers

---

<div align="center">
  <p>Developed with ❤️ by <a href="https://github.com/koussayx8">koussayx8</a></p>
</div>
