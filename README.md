  Friend Suggestion System
A smart and efficient social networking project that suggests friends to users based on mutual connections, shared interests, location, and age. Built using Flask (Python) for the backend, SQLite for data storage, and a clean HTML/CSS interface.

📌 Project Overview
This system creates a graph of user connections and uses Breadth-First Search (BFS) to suggest friends based on mutual relationships. When no mutual friends are found, it falls back to interest-based and location/age-based suggestions. User data is managed securely using an SQLite database.

🚀 Features
✅ Add and manage user profiles
✅ Store data using SQLite
✅ Suggest friends using mutual friends (via BFS)
✅ Suggest friends using shared interests if no mutuals
✅ Suggest friends using location and similar age if no interest match
✅ Simple and elegant HTML/CSS frontend
✅ Lightweight and fast Python Flask backend

 How It Works
Input: User data including name, age, location, interests, and current connections
Storage: All user information and friendships are stored in a SQLite database

Suggestion Logic:
Use BFS traversal to find friends of friends (mutual connections)
If none found, suggest based on common interests
If still none, suggest users from the same location and similar age

 Technologies Used
Backend: Python 3 (Flask)
Database: SQLite
Frontend: HTML5 and CSS3
Graph Algorithm: BFS (for mutual friend detection)
