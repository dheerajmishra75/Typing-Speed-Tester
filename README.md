# Typing Speed Tester

A simple Python command-line application that measures typing speed and character accuracy while you type a randomly selected sentence.

The project focuses on practicing Python fundamentals such as functions, lists, loops, string operations, random selection, user input, and time-based calculations.

## 🎥 Preview
[▶️ Watch Typing Speed Tester Demo](./Preview_video/Typing%20Speed%20Tester.mp4)

The preview demonstrates the terminal-based typing test, user input process, and final typing performance results.

## ✨ Features

- Randomly selects a sentence for every typing test
- Displays the selected sentence for the user
- Measures the time taken to complete the typing test
- Calculates typing speed in Words Per Minute (WPM)
- Calculates character-level typing accuracy
- Compares the typed text with the original sentence
- Displays the final typing performance in the terminal
- Uses Python standard library modules only

## 🎯 Project Overview

The Typing Speed Tester provides a simple way to practice typing while measuring basic typing performance.

A sentence is selected randomly from a predefined collection. The user then types the displayed sentence, after which the application calculates the time taken, word count, typing speed, and character accuracy.

## 🔄 How It Works

    1. The program stores multiple sentences in a Python list.
    2. A sentence is selected randomly.
    3. The selected sentence is displayed to the user.
    4. The user starts the typing test.
    5. The application records the starting time.
    6. The user types the displayed sentence.
    7. The application records the ending time.
    8. The total time taken is calculated.
    9. The number of words is calculated.
    10. Typing speed is calculated in WPM.
    11. The typed text is compared with the original sentence.
    12. Character accuracy is calculated.
    13. The final results are displayed.

## 📊 Performance Metrics

### Typing Speed

Typing speed is calculated in Words Per Minute (WPM) based on the number of words typed and the time taken.

    WPM = (Word Count / Time Taken in Seconds) × 60

### Character Accuracy

The application compares the characters entered by the user with the characters in the original sentence to calculate the percentage of matching characters.

    Accuracy = (Correct Characters / Reference Sentence Length) × 100

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Application development |
| `random` | Random sentence selection |
| `time` | Measuring typing duration |
| Lists | Storing typing-test sentences |
| Functions | Organizing application logic |
| String Operations | Word counting and character comparison |

## 📁 Project Structure

    Typing-Speed-Tester/
    │
    ├── Preview_video/
    │   └── Typing Speed Tester.mp4
    │
    ├── main.py
    │
    └── README.md

## ▶️ Run Locally

### 1. Clone the Repository

    git clone https://github.com/dheerajmishra75/Typing-Speed-Tester.git

### 2. Navigate to the Project

    cd Typing-Speed-Tester

### 3. Run the Application

    python main.py

## 🧪 Example Workflow

    The quick brown fox jumps over the lazy dog.

    Start typing the displayed sentence...

After the user completes the test, the application calculates and displays the typing performance based on the entered text and time taken.

## 📚 Python Concepts Practiced

This project helped practice fundamental Python concepts including:

- Variables and data types
- Lists
- Functions
- Loops
- Conditional statements
- String operations
- User input
- Random selection
- Time measurement
- Basic mathematical calculations
- Formatted output using f-strings

## 🎯 Learning Outcomes

Through this project, I practiced how to:

- Build an interactive command-line application using Python
- Work with Python's standard library
- Take and process user input
- Measure elapsed time
- Perform string comparison
- Calculate typing performance metrics
- Organize application logic using functions

## 🚀 Future Improvements

Possible improvements for future versions include:

- Multiple typing difficulty levels
- Larger collections of typing passages
- Custom text input
- Error count tracking
- Characters Per Minute (CPM)
- Best-score tracking
- Typing history
- Graphical User Interface (GUI)

## 🔗 Project Links

- GitHub: https://github.com/dheerajmishra75/Typing-Speed-Tester

## 👨‍💻 Author

**Dheeraj Mishra**

B.Tech CSE Student | Python | Data Science | Machine Learning | Backend Development

## 📌 Disclaimer

This project was created for learning and practice purposes. The typing speed and accuracy measurements are based on the application's implemented calculation logic and are intended as a simple typing-practice measurement rather than a professional typing assessment.
