#  Java Notes App (File I/O Task)

##  Objective
A simple **console-based Notes Manager** built in Java that allows users to **write** and **view** notes.  
This project demonstrates the use of **FileReader**, **FileWriter**, and **BufferedReader** for file handling and data persistence.

---

##  Technologies Used
- **Java**
- **VS Code / Eclipse**
- **FileWriter / FileReader / BufferedReader**
- **Exception Handling**

---

##  Features
 Add new notes (saved in a text file)  
 View all saved notes anytime  
 Data is **persistent** even after program closes  
 Uses **try-with-resources** for automatic file closing  
 Handles exceptions safely (IOException, FileNotFoundException)

---

##  How It Works
1️ User gets a simple menu:
   - Write a new note  
   - View all notes  
   - Exit  

2️ Notes are saved inside a file named **`notes.txt`**.  
3️ When the user selects "View Notes", the program reads data line-by-line using **BufferedReader**.

---

##  How to Run
1. Open terminal in your project folder.  
2. Compile the code:
   ```bash
   javac NotesApp.java
