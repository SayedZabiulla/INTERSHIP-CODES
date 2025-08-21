# Java File Handling Utility 📁

![Language](https://img.shields.io/badge/Language-Java-blue.svg)
![Platform](https://img.shields.io/badge/Platform-JVM-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A simple yet effective command-line based file management tool built in Java. This utility provides essential file operations like creating, reading, updating (appending), and deleting text files through an interactive menu. It's an excellent project for demonstrating core Java I/O concepts.

---

## ✨ Features

* **✍️ Write to File:** Create a new file or completely overwrite an existing one with new content.
* **📖 Read File:** Display the contents of any specified text file directly in the console.
* **➕ Append to File:** Add new content to the end of an existing file without deleting its original data.
* **🗑️ Delete File:** Permanently remove a file from the system.
* **🖥️ Interactive Menu:** A user-friendly, menu-driven command-line interface for easy navigation.

---

## 📋 Prerequisites

Before you begin, ensure you have the **Java Development Kit (JDK)** installed on your system. You can verify your installation by opening a terminal or command prompt and running:

```bash
java -version
javac -version
```

---

## 🚀 Getting Started

Follow these simple steps to get the application up and running.

### 1. Clone the Repository
Clone this repository to your local machine using your preferred method (HTTPS or SSH).
```bash
git clone [https://github.com/SayedZabiulla/your-repository-name.git](https://github.com/SayedZabiulla/your-repository-name.git)
```
*(Replace `your-repository-name` with the actual name of your repository.)*

### 2. Navigate to the Directory
```bash
cd your-repository-name
```

### 3. Compile the Code
Compile the Java source file. Assuming the file is named `code.java`:
```bash
javac code.java
```
This will create a `code.class` file in the same directory.

### 4. Run the Application
Execute the compiled Java code to start the utility:
```bash
java code
```

---

## 📝 Example Usage

Once the program is running, you will be greeted with an interactive menu. Below is a sample interaction:

```
--- File Handling Menu ---
1. Write to a file (creates a new file or overwrites existing)
2. Read a file
3. Append to a file
4. Delete a file
5. Exit
Enter your choice: 1

Enter filename: my_notes.txt
Enter content: This is my first note.
Successfully wrote to my_notes.txt

--- File Handling Menu ---
1. Write to a file (creates a new file or overwrites existing)
2. Read a file
3. Append to a file
4. Delete a file
5. Exit
Enter your choice: 3

Enter filename to append to: my_notes.txt
Enter content to append: This is an additional line.
Successfully wrote to my_notes.txt

--- File Handling Menu ---
1. Write to a file (creates a new file or overwrites existing)
2. Read a file
3. Append to a file
4. Delete a file
5. Exit
Enter your choice: 2

Enter filename to read: my_notes.txt

Content of my_notes.txt:
This is my first note.
This is an additional line.

--- File Handling Menu ---
1. Write to a file (creates a new file or overwrites existing)
2. Read a file
3. Append to a file
4. Delete a file
5. Exit
Enter your choice: 5
Exiting program.
```

---

## 📬 Contact

Created by **Sayed Zabiulla** - feel free to reach out!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sayed%20Zabiulla-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/sayed-zabiulla-b5bb0536b/)
[![GitHub](https://img.shields.io/badge/GitHub-SayedZabiulla-grey?style=for-the-badge&logo=github)](https://github.com/SayedZabiulla)
[![Gmail](https://img.shields.io/badge/Gmail-sayedzabeulla@gmail.com-red?style=for-the-badge&logo=gmail)](mailto:sayedzabeulla@gmail.com)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.