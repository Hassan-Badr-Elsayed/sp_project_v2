# ⚽ CounterAttack

A comprehensive console-based football management system written in C++. CounterAttack is the number one app for football fans to stay updated with their favorite teams, track match results, view leaderboards, and manage fixtures securely.

## 🚀 Features

### 🛡️ Security & Authentication
- Secure user registration and login system.
- Password hashing with dynamic salting to ensure data privacy.
- Role-based access control separating **Admin** and **User** functionalities.

### 👨‍💼 Admin Privileges
- Add new teams and remove existing ones from the league.
- Schedule upcoming matches with proper date and time formatting.
- Update results for played matches, which automatically recalculates team points and updates the leaderboard.

### 👤 User Features
- **Follow/Unfollow:** Keep track of your favorite teams.
- **Personalized Feed:** View data, points, and matches specifically for the teams you follow.
- **Match Filtering:** Search and view matches for any specific team.
- **Match Tracking:** View all upcoming and past matches across the entire league.
- **League Leaderboard:** Real-time ranking of teams based on total points and titles.
- 🏆 **Game of the Week:** A randomly generated featured match displayed upon opening the application.

## 🛠️ Tech Stack
- **Language:** C++
- **Data Persistence:** File I/O handling (`teams.txt`, `users.txt`, `matches.txt`, `follow.txt`) to save and load state automatically.
- **Core Concepts:** Structs, Pointers, Algorithms (Sorting for Leaderboard), and Cryptography (Hashing).

## 🤝 Contributors
This project was built collaboratively by our dedicated team. Each member focused on core functionalities to ensure a smooth and optimized application:

- **Hassan Badr:** Match display functionality (All, Past, Upcoming) and Unfollow team mechanics.
- **Ibrahim:** System architecture (Structs declarations) and File I/O handling (`SaveData`, `LoadData`).
- **Muhammad:** Follow team mechanics, Match filtering, Menu structures, and string manipulation (`AddUnderScore`, `RemoveUnderScore`).
- **Youssef:** Team addition and Upcoming Match scheduling logic.
- **Hassan Tarek:** Match result updating and League Leaderboard sorting algorithm.
- **Joe:** Authentication system (Register, Login, Logout) and Security (Password Hashing & Salting).
- **Moaz:** Followed-Teams matches feed, Removing Teams, and Game of the Week feature.
