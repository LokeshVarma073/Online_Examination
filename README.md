# ExamEase – Online Examination System

A browser-based multiple-choice examination project built with HTML, CSS and JavaScript.

## Features
- Student login using name and student ID
- 10 multiple-choice questions
- Question palette and previous/next navigation
- Answer selection and browser LocalStorage saving
- 10-minute countdown timer with automatic submission
- Automatic score, percentage, pass/fail and answer summary
- Retake and return-home options
- Responsive interface

## Project structure
```text
OnlineClass-Ass/
├── css/style.css
├── html/
│   ├── index.html
│   ├── exam.html
│   └── result.html
└── js/
    ├── login.js
    ├── exam.js
    └── result.js
```

## Run
Open the `OnlineClass-Ass` folder in VS Code, start Live Server, and open:
`html/index.html`

No Java server or internet connection is required for the exam functionality. Google Fonts are optional; fallback fonts are included.

## Notes
This is a frontend academic demonstration. LocalStorage is browser-based and is not secure authentication or server-side exam validation.
