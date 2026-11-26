# 📝 Online Quiz System

![Java](https://img.shields.io/badge/Java-19-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-19-007396?style=flat-square)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

A desktop quiz app built with **JavaFX**. A teacher writes a 10-question multiple-choice quiz, and a student takes it against a **10-minute timer** and gets their mark right away. ⏱️

I built it to learn **JavaFX, FXML layouts and scene switching**, and to connect two different user flows through shared data.

---

## ✨ Features

### 👩‍🏫 Teacher
- Write **10 questions**, each with **4 options**
- Set the correct option for every question
- Save the quiz (stored in `question.txt` and `answer.txt`)

### 🧑‍🎓 Student
- Start the quiz and answer all 10 questions
- **10-minute countdown**; the quiz locks when time is up
- Submit and instantly see the score, like `Mark: 8/10`

## 🚀 Run it

**Requirements:** JDK 19+ and Maven.

```bash
cd "Online Quiz Management System"
mvn clean javafx:run
```

Or open the folder in **IntelliJ IDEA** and run `Main.java`.

## 📁 Project structure

```text
Online Quiz Management System/
├── pom.xml
├── question.txt / answer.txt         # Saved quiz data
└── src/main/
    ├── java/com/example/onlinequizmanagementsystem/
    │   ├── Main.java                 # App entry point
    │   ├── MainController.java       # Teacher / Student choice
    │   ├── TeacherController.java    # Create the quiz
    │   └── StudentController.java    # Take the quiz + timer + scoring
    └── resources/.../
        ├── main.fxml
        ├── teacher.fxml
        └── student.fxml
```

## 🛠️ Built with

- ☕ Java 19
- 🎨 JavaFX 19 + FXML
- 📦 Maven

---

Made by **Abdullah Al Jubayer** · [GitHub](https://github.com/abdullahaljubayer-101) · [Portfolio](https://abdullahaljubayer.com)
