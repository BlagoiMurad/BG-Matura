****
# 🇧🇬 Bulgarian Matura Preparation Platform

> 🎓 A modern web platform for preparing for the Bulgarian Language and Literature State Matura (ДЗИ по БЕЛ).

[![Status](https://img.shields.io/badge/status-in%20development-orange)](#)
[![License](https://img.shields.io/badge/license-MIT-green)](#license)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](#)

---

## 📖 About

**Bulgarian Matura Preparation Platform** is an educational web application designed to help Bulgarian students prepare for the **Bulgarian Language and Literature State Matura**.

The platform combines learning materials, interactive exercises, mock exams and progress tracking in one place.

Instead of studying from scattered resources, students can use a single platform to:

- 📚 Learn theory
- 📝 Practice questions
- 🧪 Take simulated exams
- ❌ Review mistakes
- 📊 Track their progress
- 🎯 Focus on weak topics

### The main idea

```text
       LEARN
         ↓
      PRACTICE
         ↓
        TEST
         ↓
      ANALYZE
         ↓
       IMPROVE
         ↓
       SUCCEED
```

---

# 🎯 Project Goal

The goal of the project is to make Matura preparation:

**Simple · Interactive · Organized · Measurable**

The application focuses on giving students immediate feedback and showing them exactly where they need to improve.

---

# ✨ Features

## 📚 Learning Materials

Students can study different areas of Bulgarian language and literature:

- Grammar
- Spelling
- Punctuation
- Syntax
- Vocabulary
- Morphology
- Text comprehension
- Literary terminology
- Bulgarian literature
- Exam preparation strategies

---

## 📝 Interactive Practice

Students can practice questions by topic.

Each question provides:

- Multiple-choice answers
- Immediate feedback
- Correct answer
- Explanation
- Score tracking

Example:

```text
┌─────────────────────────────────────────────┐
│ Question 12                                 │
│                                             │
│ Which sentence is grammatically correct?    │
│                                             │
│ ○ Answer A                                  │
│ ○ Answer B                                  │
│ ● Answer C                                  │
│ ○ Answer D                                  │
│                                             │
│              [ Check Answer ]               │
└─────────────────────────────────────────────┘
```

---

# 🧪 Mock Matura Exams

The platform includes full simulated exams designed to reproduce the experience of taking a real test.

A mock exam includes:

- ⏱️ Countdown timer
- 📄 Exam-style questions
- 📊 Automatic scoring
- ✅ Correct answers
- ❌ Incorrect answers
- 📈 Performance analysis

After completing the exam, the student receives a detailed result.

```text
┌──────────────────────────────────────┐
│           MOCK EXAM #4               │
├──────────────────────────────────────┤
│                                      │
│ Score            82 / 100            │
│ Accuracy         82%                 │
│                                      │
│ Correct          82                  │
│ Incorrect        18                  │
│                                      │
│ Strongest topic  Spelling            │
│ Weakest topic    Punctuation         │
│                                      │
│          [ Review Mistakes ]         │
└──────────────────────────────────────┘
```

---

# 📊 Personal Dashboard

Every student has a personal dashboard showing their current performance.

### Example

```text
Hello, Student 👋

────────────────────────────────────

Average Score       84%
Questions Solved    342
Quizzes Completed   27
Study Streak        8 days

────────────────────────────────────

YOUR PERFORMANCE

Grammar        ████████░░  80%
Spelling       █████████░  90%
Vocabulary     ███████░░░  70%
Syntax         █████░░░░░  50%
Punctuation    ████░░░░░░  40%

────────────────────────────────────

🎯 Recommended

Practice Punctuation

Your current accuracy: 40%

[ Start Practice ]
```

---

# ❌ Mistake Review

One of the main features of the platform is the **Mistakes** section.

Incorrect questions are automatically saved so students can return to them later.

```text
MY MISTAKES

❌ Punctuation — Question #23
❌ Grammar — Question #17
❌ Syntax — Question #12
❌ Vocabulary — Question #41
```

The goal is not simply to show the score, but to help the student understand **why the answer was wrong**.

---

# 🎯 Personalized Practice

The system analyzes the student's results and identifies weak areas.

For example:

```text
Performance

Spelling       █████████░ 90%
Grammar        ████████░░ 80%
Vocabulary     ███████░░░ 70%
Syntax         █████░░░░░ 50%
Punctuation    ████░░░░░░ 40%
```

The platform can then recommend:

> **You should practice Punctuation next.**

This turns the application from a simple quiz website into a **personalized learning platform**.

---

# 👥 User Roles

## 👨‍🎓 Student

Students can:

- Create an account
- Log in
- Study topics
- Practice questions
- Take mock exams
- View results
- Review mistakes
- Track progress

---

## 👨‍🏫 Teacher

Teachers can:

- Create questions
- Edit questions
- Delete questions
- Create learning materials
- Manage topics
- Review student performance

---

## 🛠️ Administrator

Administrators can:

- Manage users
- Manage teachers
- Manage questions
- Manage categories
- Manage learning materials
- Moderate platform content

---

# 🔄 Application Flow

```text
                    ┌─────────────┐
                    │   Landing   │
                    │    Page     │
                    └──────┬──────┘
                           │
                    ┌──────▼──────┐
                    │ Register /  │
                    │    Login    │
                    └──────┬──────┘
                           │
                    ┌──────▼──────┐
                    │  Dashboard  │
                    └──────┬──────┘
                           │
           ┌───────────────┼────────────────┐
           │               │                │
      ┌────▼────┐     ┌────▼────┐     ┌────▼────┐
      │  Learn  │     │ Practice│     │   Exam  │
      └────┬────┘     └────┬────┘     └────┬────┘
           │               │                │
           └───────────────┼────────────────┘
                           │
                    ┌──────▼──────┐
                    │   Results   │
                    └──────┬──────┘
                           │
                    ┌──────▼──────┐
                    │  Progress   │
                    └─────────────┘
```

---

# 🛠️ Technology Stack

### Frontend

- **HTML5**
- **CSS3**
- **JavaScript**

### Data & Logic

- JavaScript application logic
- Local Storage for the initial version

### Development

- Git
- GitHub
- Visual Studio Code
- Browser DevTools

### Future Backend

The architecture can later be extended with:

- REST API
- Backend application
- SQL database
- Authentication service
- Teacher/Admin panel

---

# 🏗️ Architecture

Current architecture:

```text
┌─────────────────────────────┐
│          Browser            │
│                             │
│  HTML → CSS → JavaScript    │
│              │              │
│              ├── Quiz       │
│              ├── Auth       │
│              ├── Progress   │
│              ├── Dashboard  │
│              └── Storage    │
│                             │
└─────────────────────────────┘
```

Future architecture:

```text
┌───────────────┐
│   Frontend    │
│ HTML/CSS/JS   │
└───────┬───────┘
        │
        │ REST API
        ▼
┌───────────────┐
│    Backend    │
│               │
│ Authentication│
│ Quiz Engine   │
│ Progress      │
│ Admin Panel   │
└───────┬───────┘
        │
        ▼
┌───────────────┐
│   Database    │
│               │
│ Users         │
│ Questions     │
│ Results       │
│ Materials     │
└───────────────┘
```

---

# 📁 Project Structure

```text
bulgarian-matura-platform/
│
├── index.html
├── login.html
├── register.html
├── dashboard.html
├── topics.html
├── quiz.html
├── results.html
├── mistakes.html
├── profile.html
│
├── css/
│   ├── style.css
│   ├── responsive.css
│   └── components.css
│
├── js/
│   ├── app.js
│   ├── auth.js
│   ├── quiz.js
│   ├── questions.js
│   ├── progress.js
│   ├── dashboard.js
│   └── storage.js
│
├── data/
│   ├── questions.js
│   └── topics.js
│
├── assets/
│   ├── images/
│   └── icons/
│
└── README.md
```

---

# 🗃️ Data Model

### Question

```javascript
{
    id: 1,
    category: "Grammar",
    question: "Which sentence is grammatically correct?",
    answers: [
        "Answer A",
        "Answer B",
        "Answer C",
        "Answer D"
    ],
    correctAnswer: 2,
    explanation: "Explanation of the correct answer."
}
```

### User

```javascript
{
    id: 1,
    username: "student123",
    email: "student@example.com",
    role: "student",
    progress: {
        completedQuizzes: 12,
        averageScore: 84,
        accuracy: 87
    }
}
```

---

# 📈 Scoring

Each correct answer gives one point.

```text
Correct answer   → +1
Incorrect answer → +0
```

Percentage:

```text
correctAnswers / totalQuestions × 100
```

Example:

```text
18 correct answers
20 total questions

18 / 20 × 100 = 90%
```

The application may also provide an **estimated grade**, but this should not be confused with the official Matura grading methodology.

---

# 🔐 Security

The application follows basic security principles:

- Input validation
- Protected user pages
- Role-based access
- No plain-text passwords in a future backend
- Secure authentication
- Validation of user-generated content

When a backend is introduced, passwords should be stored using a secure password-hashing algorithm.

---

# 📱 Responsive Design

The platform is designed to work across:

- 💻 Desktop
- 💻 Laptop
- 📱 Mobile
- 📲 Tablet

The interface adapts to smaller screens while keeping the quiz experience easy to use.

---

# 🧪 Testing

Testing will cover:

### Authentication

- Registration
- Login
- Logout
- Invalid credentials
- Form validation

### Quiz

- Question loading
- Answer selection
- Answer validation
- Score calculation
- Result generation

### Progress

- Result storage
- Statistics
- Accuracy calculation
- Mistake tracking

### Responsive UI

- Desktop
- Tablet
- Mobile

---

# 🗺️ Roadmap

## ✅ Phase 1 — MVP

- [x] Project structure
- [ ] Authentication
- [ ] Learning materials
- [ ] Topic-based practice
- [ ] Quiz engine
- [ ] Results
- [ ] Basic dashboard

## 🚧 Phase 2 — Progress

- [ ] Advanced statistics
- [ ] Mistake review
- [ ] Performance charts
- [ ] Topic recommendations
- [ ] Study streak

## 🔮 Phase 3 — Gamification

- [ ] XP system
- [ ] Levels
- [ ] Achievements
- [ ] Badges
- [ ] Daily challenges
- [ ] Leaderboards

## 🤖 Phase 4 — AI

- [ ] AI explanations
- [ ] Personalized exercises
- [ ] AI tutor
- [ ] Automatic question generation

## ☁️ Phase 5 — Backend

- [ ] REST API
- [ ] Database
- [ ] User authentication
- [ ] Teacher dashboard
- [ ] Admin panel
- [ ] Cloud deployment

---

# 🚀 Getting Started

## 1. Clone the repository

```bash
git clone https://github.com/your-username/bulgarian-matura-platform.git
```

## 2. Open the project

```bash
cd bulgarian-matura-platform
```

## 3. Run the application

The current version can be opened directly through `index.html`.

For development, **VS Code + Live Server** is recommended.

---

# 🎓 Educational Concept

The platform is based on a simple principle:

> **Don't just practice more. Practice what you don't know.**

Instead of giving every student the same experience, the application can use their results to determine which topics need additional attention.

```text
                 Student
                    │
                    ▼
               Take Quiz
                    │
                    ▼
              Analyze Result
                    │
          ┌─────────┴─────────┐
          ▼                   ▼
       Strong               Weak
       Topics               Topics
          │                   │
          │                   ▼
          │              More Practice
          │                   │
          └─────────┬─────────┘
                    ▼
                 Improve
```

---

# 🌟 Future Vision

The long-term goal is to develop the platform into a complete digital environment for Bulgarian Matura preparation.

Future versions could combine:

**Learning + Practice + AI + Analytics + Gamification**

into one system.

The ultimate goal is simple:

# 🇧🇬 Learn smarter. Practice better. Ace the Matura.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

Developed as an educational software project focused on:

- Web Development
- JavaScript
- UI/UX
- Educational Technology
- Interactive Learning

---

<p align="center">
  Made with ❤️ for Bulgarian students 🇧🇬
</p>
