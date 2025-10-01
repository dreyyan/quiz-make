# QuizMake
_Quiz Desktop Application for Students and Learners via PyQt_

**QuizMake** is a Python-based desktop application built with PyQt, designed to create and manage interactive quizzes for students and learners. With a user-friendly graphical interface, QuizMake enables educators and learners to build, take, and track quizzes, fostering an engaging learning experience. The application aims to simplify quiz creation and administration, making it ideal for educational settings or self-study.

The primary purpose of QuizMake is to provide a customizable platform for quiz-based learning, supporting students and educators in testing knowledge and tracking progress through a polished desktop interface.

## FEATURES
✅ **Quiz Creation** – Design custom quizzes with various question types.  
✅ **Interactive GUI** – Navigate and take quizzes via a PyQt-based desktop interface.  
✅ **Progress Tracking** – Monitor quiz results and learner performance.  
✅ **User-Friendly Design** – Intuitive controls for educators and students.  

## FUTURE IMPLEMENTATIONS
🚀 **Question Bank** – Store and reuse questions across multiple quizzes.  
🚀 **Timed Quizzes** – Add timers for timed assessments.  
🚀 **Export/Import Quizzes** – Support for saving and sharing quizzes in formats like JSON or CSV.  
🚀 **Multi-User Support** – Enable accounts for teachers and students with role-based access.  

## UPDATES
🔄 Initial GUI implementation with PyQt for quiz creation and interaction.  
🔄 Basic quiz-taking and result-tracking functionality added.  
🔄 Ongoing refinements to interface usability and performance.  

## PROJECT DETAILS
📌 **Author:** dreyyan  
📌 **Started:** 2024-10-29  
📌 **Finished:** 2024-11-01 (Temporarily discontinued)  

## TECH STACK
🛠️ **Language:** Python  
🛠️ **Libraries:** PyQt  

## INSTALLATION
### Prerequisites
- Python 3.8 or higher
- Create a virtual environment (recommended):
  ```
  python -m venv venv
  source venv/bin/activate  # On Unix/Mac
  venv\Scripts\activate     # On Windows
  ```

### Install Dependencies
Install PyQt:
```
pip install PyQt5
```

### Verify Installation
Check PyQt installation:
```
python -c "import PyQt5; print(PyQt5.__version__)"
```

## USAGE
### Running the Application
Start QuizMake from the project root:
```
python main.py
```

### Example Workflow
1. **Launch the App**: Run `python main.py` to open the PyQt desktop interface.
2. **Create a Quiz**: Use the GUI to design a quiz with custom questions.
3. **Take a Quiz**: Select a quiz and answer questions interactively.
4. **View Results**: Check scores and performance feedback.

### Configuration
- No external configuration files required; settings are managed within the PyQt interface.
- Ensure sufficient screen resolution for optimal GUI display.

## DEBUGGING
For issues, check console output for PyQt-related errors or quiz logic issues. Run with:
```
python main.py
```
Report issues via GitHub Issues for detailed troubleshooting.

## PROJECT STRUCTURE
- `main.py`: Entry point for the application (assumed; adjust based on actual structure).
- Other files may include modules for quiz logic, GUI components, and data management (not specified in provided details).

## CONTRIBUTING
Contributions are welcome! Fork the repo, make changes, and submit a pull request:
1. Create a feature branch: `git checkout -b feature/new-feature`
2. Commit changes: `git commit -m "Add new feature"`
3. Push: `git push origin feature/new-feature`
4. Open a pull request

Report issues or suggest features via GitHub Issues.

## LICENSE
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.