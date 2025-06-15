# History Quiz Web App

A simple, interactive web-based History Quiz built with Python and Flask. Test your knowledge of world history with multiple-choice questions in a visually engaging interface, now fully localized in Bulgarian!

## Features

- Multiple-choice world history questions (in Bulgarian)
- Instant feedback and scoring
- Retake quiz functionality
- Responsive and visually appealing design with a historical background
- All questions displayed at once for easy navigation

## Installation

### Local Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/SvetoslavIvanov98/quiz-app.git
   cd history-quiz
   ```

2. **Create a virtual environment (optional but recommended):**
   ```sh
   python -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```sh
   pip install flask
   ```

4. **Run the app:**
   ```sh
   python app.py
   ```

5. **Open your browser and go to:**
   ```
   http://localhost:5000
   ```

---

### Docker Installation

1. **Navigate to the Docker directory:**
   ```sh
   cd Docker
   ```

2. **Build the Docker image:**
   ```sh
   docker build -t history-quiz .
   ```

3. **Run the Docker container:**
   ```sh
   docker run -p 5000:5000 history-quiz
   ```

4. **Open your browser and go to:**
   ```
   http://localhost:5000
   ```

---

## Project Structure

```
history-quiz/
├── app.py
├── questions.py
├── static/
│   ├── history-bg.jpg
│   └── style.css
├── templates/
│   └── index.html
└── Docker/
    ├── Dockerfile
    └── .dockerignore
```

## Customization

- **Add or edit questions:**  
  Modify [`questions.py`](questions.py) to add your own quiz questions in Bulgarian language.
- **Change background:**  
  Replace [`static/history-bg.jpg`](static/history-bg.jpg) with your preferred image.
- **Style the app:**  
  Edit [`static/style.css`](static/style.css) for custom styles.

## License

This project is licensed under the MIT License.

---

*Made with Flask and ❤️ for history lovers!*