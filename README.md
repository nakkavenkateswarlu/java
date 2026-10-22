# Student Grade Tracker

## 📌 Project Overview

**Student Grade Tracker** is a Java-based console application developed to manage and analyze student grades. The application allows users to enter multiple student grades, validates the input, and generates a summary report containing the average, highest, and lowest scores.

This project was developed as part of the **Java Developer Internship at CodeAlpha** to practice core Java programming concepts, input handling, collections, loops, validation, and basic data processing.

## ✨ Features

- Enter multiple student grades through the console.
- Use `-1` to stop entering grades.
- Validate grades within the range of **0–100**.
- Handle invalid non-numeric inputs.
- Calculate the **average score**.
- Find the **highest score**.
- Find the **lowest score**.
- Display all entered grades.
- Handle cases where no grades are entered.

## 🛠️ Technologies Used

- **Java**
- **Java Collections Framework**
- `ArrayList`
- `Scanner`
- `Collections.max()`
- `Collections.min()`

## ⚙️ How It Works

The application follows a simple workflow:

1. The program starts and displays instructions.
2. The user enters student grades one by one.
3. Each grade is validated to ensure it is between `0` and `100`.
4. Valid grades are stored in an `ArrayList`.
5. The user enters `-1` to finish the input process.
6. The application calculates:
   - Average score
   - Highest score
   - Lowest score
7. Finally, all entered grades are displayed in the summary report.

## 📂 Project Structure

```text
StudentGradeTracker/
│
├── java task-1.java
└── README.md
```


## 🚀 How to Run

### Prerequisites

Make sure **Java JDK** is installed on your system.

Check the Java installation:

```bash
java -version
```

Check the Java compiler:

```bash
javac -version
```

### Compile the Program

Open a terminal in the project directory and run:

```bash
javac StudentGradeTracker.java
```

### Run the Program

```bash
java StudentGradeTracker
```

## 🧪 Sample Execution

```text
Welcome to the Student Grade Tracker!
Enter student grades one by one. Enter -1 to finish.

Enter grade (or -1 to stop): 85
Enter grade (or -1 to stop): 72
Enter grade (or -1 to stop): 91
Enter grade (or -1 to stop): 66
Enter grade (or -1 to stop): -1

--- Grade Summary Report ---
Average Score: 78.50
Highest Score: 91
Lowest Score: 66
All Entered Grades: [85, 72, 91, 66]

Thank you for using the Student Grade Tracker!
```

## 📚 Java Concepts Practiced

This project demonstrates the following Java concepts:

- Variables and data types
- `Scanner` for user input
- `while` loops
- `for-each` loops
- Conditional statements
- Input validation
- Exception-prevention through input checking
- `ArrayList`
- Java Collections
- Arithmetic calculations
- Formatted output
- Console-based application development

## 🔮 Future Enhancements

Possible improvements for future versions include:

- Store student names along with grades.
- Calculate letter grades such as A, B, C, D, and F.
- Generate individual student reports.
- Add a graphical user interface (GUI).
- Store grades in a file or database.
- Add sorting and ranking functionality.
- Support multiple subjects for each student.

## 🎓 Internship

**Internship:** Java Developer Internship  
**Organization:** CodeAlpha  
**Project:** Student Grade Tracker

This project provided practical experience in developing a Java console application and applying fundamental programming and data-structure concepts to a real-world use case.

## 👨‍💻 Author

**Nakka Venkateswarlu**

GitHub: `https://github.com/nakkavenkateswarlu/java`

---

⭐ If you found this project useful, consider giving the repository a star!
