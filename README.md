# Fake News Detection System

## 1. Project Overview

The Fake News Detection System is a Python-based machine learning project that aims to classify news text as potentially fake or real. The system will analyze a news headline or article and predict its classification based on patterns learned from a labeled dataset.

This project is being developed as part of the **Software Construction and Development** course.

## 2. Problem Statement

The spread of misleading information on the internet makes it difficult for readers to judge the credibility of news articles. Manually checking every news item can take time. This project aims to demonstrate how machine learning can help classify news text automatically.

The system will provide predictions based on learned patterns and will not independently verify the factual accuracy of an article.

## 3. Project Objectives

- Develop a machine learning model for news text classification.
- Allow users to enter a news headline or article.
- Display the predicted classification through a simple interface.
- Evaluate the model using appropriate performance metrics.
- Practice collaborative software development using Git and GitHub.

## 4. Planned Technologies

- **Programming Language:** Python
- **Development Environment:** Visual Studio Code
- **Data Processing:** Pandas
- **Machine Learning:** Scikit-learn
- **User Interface:** Streamlit
- **Version Control:** Git and GitHub

## 5. Planned Features

- Accept news headlines or article text as input.
- Validate input and handle empty text.
- Preprocess text before classification.
- Predict whether the text resembles fake or real news examples from the training dataset.
- Evaluate model performance using accuracy, precision, recall, and F1-score.
- Provide a simple and understandable user interface.

## 6. Group Members

| No. |      Name    | Responsibility |
|---|---|---|---|
| 1 | [Hamdan Yasir] | Repository and documentation |
| 2 | [Idrees Zazai] | Dataset preparation |
| 3 | [Farman Afridi]| Model development and evaluation |


## 7. Repository Structure

```text
Semester-Python-Project/
├── README.md
├── TASKS.md
├── requirements.txt
├── .gitignore
├── docs/
│   └── requirements.md
├── data/
├── models/
└── app.py
```

The project structure may change as development progresses. The `data` directory will contain dataset-related files, `models` will store trained model files, and `app.py` will contain the application interface.

## 8. Development Status

**Current Status:** Project initiation and requirements planning.

The team is currently preparing the requirements document, organizing the repository, and assigning responsibilities. Dataset preparation, model development, evaluation, and interface implementation are planned for later stages.

## 9. Collaboration and Version Control

The team will use Git and GitHub to manage the project and track changes. Each group member will contribute through their own GitHub account.

Commit messages will describe the changes made. Important development milestones will be marked using Git tags.

## 10. Limitations

- Prediction quality will depend on the dataset and training process.
- The model may perform differently on unfamiliar news sources or topics.
- The system will identify patterns learned from labeled examples rather than independently establish factual truth.
- The initial version will focus on English-language news text.
- Live fact-checking is outside the initial project scope.

## 11. Future Improvements

Possible future improvements include testing additional machine learning algorithms, improving the interface, expanding the dataset, and supporting further evaluation methods.

## 12. Academic Information

**Course:** Software Construction and Development  
**Instructor:** Engr. Muhammad Umer Haroon  
**Project:** Fake News Detection System

---

*This project is developed for educational purposes. Its predictions should not be treated as definitive proof that a news article is true or false.*