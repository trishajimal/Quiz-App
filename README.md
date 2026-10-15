# Quiz App

A lightweight web-based quiz application built with HTML, CSS, and JavaScript. It presents multiple-choice questions, highlights the correct answer after selection, tracks the user's score, and lets the user move through the quiz or restart it at the end.

## Features

- Multiple-choice quiz questions
- Score tracking
- Visual feedback for correct and incorrect answers
- Next question flow
- Replay option after finishing the quiz
- Responsive and simple layout

## Project Structure

- `index.html` — page structure and quiz container
- `style.css` — styling and layout
- `script.js` — quiz logic and question data

## How to Run

Because this is a static website, you can either:

1. Open `index.html` directly in a browser, or
2. Serve it locally with a simple HTTP server.

Example using Python:

```bash
cd "c:\Users\Acer\VS CODE\Quiz App"
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How to Customize the Quiz

Edit the `questions` array in `script.js`. Each question object follows this format:

```javascript
{
  question: "Your question here",
  answers: [
    { text: "Option 1", correct: false },
    { text: "Option 2", correct: true },
    { text: "Option 3", correct: false },
    { text: "Option 4", correct: false }
  ]
}
```

Set `correct: true` on the correct answer for each question.

## Technologies Used

- HTML5
- CSS3
- JavaScript

## License

This project is open for learning and personal use.
