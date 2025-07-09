# 🌐 Language Detection Using Machine Learning Algorithms

A Machine Learning-based system to automatically detect the language of a given text using the **Multinomial Naive Bayes** classifier. This project demonstrates Natural Language Processing (NLP) techniques applied to language classification.

---

## 📄 Table of Contents
- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Algorithm Used](#algorithm-used)
- [Installation](#installation)
- [Usage](#usage)
- [Sample Output](#sample-output)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

---

## 📖 About

Language detection plays a vital role in various multilingual applications such as translation systems, chatbots, content filtering, and social media analytics.  
This project uses **Natural Language Processing (NLP)** techniques along with **Machine Learning** to classify the input text into one of the many supported languages.

---

## ✨ Features

- Supports detection of multiple languages.
- Uses the Multinomial Naive Bayes classifier.
- Simple and fast model for real-time predictions.
- Clean and easy-to-read Python code.
- Can be extended to support more languages and algorithms.

---

## 🧰 Tech Stack

- **Programming Language:** Python
- **Libraries & Tools:**  
  - `pandas`  
  - `scikit-learn`  
  - `numpy`  
  - `NLTK`  
  - `Jupyter Notebook` / Python script

---

## 📊 Dataset

- **Source:** [GitHub - Language Dataset](https://raw.githubusercontent.com/amankharwal/Website-data/master/dataset.csv)  
- **Description:** The dataset contains text samples in multiple languages along with their labels (language name).

---

## 🧠 Algorithm Used

- **Multinomial Naive Bayes:**  
  A probabilistic learning method based on Bayes' Theorem, particularly effective for discrete features like word counts or frequencies.

---

# SAMPLE-OUTPUTS :

![Screenshot 2025-04-13 193601](https://github.com/user-attachments/assets/ea857ed3-f044-409b-9e88-c83cd6f15e46)

# It has 22 languages 

![Screenshot 2025-04-13 194313](https://github.com/user-attachments/assets/ed6bc9a3-fe06-4226-a0ef-d07682766f84)

# PERFORMANCE METRICS 

![Screenshot 2025-04-13 220334](https://github.com/user-attachments/assets/b1f74a4a-be70-4eb8-99f3-57f40b035cf6)

#CONFUSION MATRIX

![Figure_1](https://github.com/user-attachments/assets/057faec3-c589-44b7-a411-cf5557635393)

---

## ⚙️ Installation

Make sure Python and pip are installed. Then, run the following:

  ```bash
  # Clone the repository
  git clone https://github.com/yourusername/language-detection-ml.git
  cd language-detection-ml
  
  # Install dependencies
  pip install pandas scikit-learn numpy nltk
