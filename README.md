📚 Library Management System

🚀 Project Overview

This project is a simple Library Management System built using Python. It allows users to manage books through a menu-driven interface where they can add, view, issue, and return books.

The system also uses JSON file handling to store data permanently, ensuring that book records are not lost after restarting the program.


🧠 Features

- ➕ Add new books
- 📖 View all books
- 📕 Issue books
- 📗 Return books
- 💾 Save data in library.json
- 🔄 Load saved data automatically on startup


🛠️ Technologies Used

- Python
- JSON (File Handling)

  
📂 Project Structure

Library-Management-System/
│── Library Management System.ipynb / .py
│── library.json
│── README.md


▶️ How to Run

If using Python file:
python main.py
If using Jupyter Notebook:
1. Open Jupyter Notebook
2. Open Library Management System.ipynb
3. Run all cells


🎮 How It Works

After running the program, you will see a menu:

1. Add Book
2. View Books
3. Issue Book
4. Return Book
5. Exit

👉 Enter the number to perform operations.

💡 Example Execution

Enter choice: 1
Enter book title: Python Basics
Book added

Enter choice: 2

Library Books:
1. Python Basics - Available

   
⚠️ Important Note

- The file library.json is created only when the program is exited using option 5 (Exit).
- This file stores all book data permanently.
- Even after restarting the program, previously added books will be loaded automatically.


🧠 Concepts Used

- Lists and Dictionaries
- Functions
- Loops and Conditionals
- Exception Handling
- File Handling (JSON)
- User Input Handling


🎯 Learning Outcomes

- Built a real-world mini application
- Learned how to manage and persist data
- Implemented menu-driven logic
- Handled user input and edge cases
- Understood state management using Boolean flags


🚀 Future Improvements

🔍 Search book feature
🗑️ Delete book option
👤 User login system
📅 Due date & fine system
🖥️ GUI version (Tkinter / Streamlit)


👨‍💻 Author

Kousik Chakraborty


⭐ Conclusion

This project demonstrates how to build a structured Python application with real-world functionality such as data persistence, user interaction, and state management.
