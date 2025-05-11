# Multilingual Quiz App

![Quiz App Banner](https://framerusercontent.com/images/9vH8BcjXKRcC5OrSfkohhSyDgX0.png)

A powerful, interactive Streamlit application that allows users to create, take, and track quizzes in 50+ languages using the Sutra LLM model and Educhain framework.

## 🌟 Features

### Multilingual Support
- Create and take quizzes in **50+ languages** including English, Hindi, Spanish, French, Chinese, Arabic, and more
- Complete multilingual support for questions, options, answers, and explanations

### Quiz Creation
- Generate multiple-choice and true/false questions automatically
- Choose difficulty levels: Easy, Medium, or Hard
- Customize number of questions (3-10)
- Add custom instructions to tailor quiz content

### Quiz Management
- Save generated quizzes for later use
- Browse all saved quizzes in a sortable table
- Delete quizzes you no longer need

### Interactive Quiz Experience
- Take quizzes with an intuitive, user-friendly interface
- Track progress with a progress bar
- Get immediate feedback on answers
- Review detailed explanations for each question
- See your final score with performance analysis

### Performance Tracking
- View history of all quiz attempts
- Track performance by topic with detailed analytics
- Visualize progress with charts and graphs

## 📋 Requirements

- Python 3.7+
- Streamlit
- Educhain
- LangChain
- Sutra LLM API access

## 🚀 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Bharath880/Quiz_App.git
   cd Quiz_App
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Sutra API key:
   - Option 1: Create a `.env` file with:
     ```
     SUTRA_API_KEY=your_api_key_here
     ```
   - Option 2: Set it as an environment variable:
     ```bash
     export SUTRA_API_KEY=your_api_key_here
     ```
   - Option 3: Enter it directly in the app's sidebar

4. Run the application:
   ```bash
   streamlit run quiz_app.py
   ```

## 📱 Usage

### Creating a Quiz
1. Navigate to the "Create Quiz" page
2. Select your preferred language, question type, and difficulty level
3. Enter the quiz topic and number of questions
4. Add any custom instructions (optional)
5. Click "Generate Quiz"
6. Preview your quiz and start it immediately or save it for later

### Taking a Quiz
1. Navigate to the "Saved Quizzes" page
2. Select a quiz from the list
3. Click "Start Selected Quiz"
4. Answer each question by clicking on your chosen option
5. Review your results at the end
6. Explore detailed explanations for each question

### Tracking Progress
1. Navigate to the "Quiz History" page
2. View your performance across all quizzes
3. Analyze your strengths and weaknesses by topic
4. Track your improvement over time

## 🧩 Project Structure

```
multilingual-quiz-app/
├── quiz_app.py              # Main application file
├── .env                     # Environment variables (create this)
├── requirements.txt         # Package dependencies
├── saved_quizzes.json       # Persistent storage for quizzes
├── quiz_history.json        # Persistent storage for history
└── README.md                # This file
```

## 📚 Technology Stack

- **Streamlit**: For the interactive web interface
- **Educhain**: Framework for educational content generation
- **LangChain**: For LLM orchestration
- **Sutra LLM**: Multilingual language model for content generation
- **Pandas**: For data manipulation and analytics

## 🛠️ Future Enhancements

- User authentication and profiles
- More question types (fill-in-the-blank, short answer)
- Export quizzes in various formats (PDF, Word)
- Collaborative quiz creation and sharing
- Timed quiz mode
- Mobile-optimized interface

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👏 Acknowledgements

- [Educhain](https://github.com/satvik314/educhain) for the educational content generation framework
- [Sutra LLM](https://docs.two.ai/) for multilingual capabilities
- [Streamlit](https://streamlit.io/) for the web app framework

---

Created with ❤️ using Sutra LLM and Educhain
