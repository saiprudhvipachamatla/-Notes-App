# Notes App (Java File I/O)

## 📌 Overview
A simple **text-based Notes Manager** built in Java using **FileReader**, **BufferedReader**, and **FileWriter**.  
This app allows you to:
- Add notes
- View all saved notes
- Persist data in a `.txt` file

## 🛠️ Tools & Technologies
- Java
- VS Code / Any IDE
- Terminal

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/notes-app-java.git
   cd notes-app-java
   ```

2. **Compile the Java File**
   ```bash
   javac NotesApp.java
   ```

3. **Run the Program**
   ```bash
   java NotesApp
   ```

## 📂 File Structure
```
notes-app-java/
│
├── NotesApp.java      # Main Java program
├── notes.txt          # Notes data file (auto-created)
└── README.md          # Documentation
```

## 💡 Features
- **Add a note** → Appends your note to `notes.txt`
- **View notes** → Reads and displays all saved notes
- Data is stored **persistently** in a text file

## 🎯 Learning Outcome
You will learn how to:
- Use `FileWriter` to write data
- Use `FileReader` / `BufferedReader` to read data
- Handle file I/O exceptions in Java

## 📝 Example Usage
```
===== Notes App =====
1. Add a note
2. View all notes
3. Exit
Enter your choice: 1
Enter your note: Finish Java File I/O project
Note saved successfully!

===== Notes App =====
1. Add a note
2. View all notes
3. Exit
Enter your choice: 2

--- Your Notes ---
- Finish Java File I/O project
```

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
