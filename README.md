# DS101-Lifecycle: Data Science Lifecycle for Beginners

Welcome to **DS101-Lifecycle**, an introductory course on the Data Science Lifecycle designed for beginners with a mathematics and statistics background. This course guides you through all six phases—**Problem Formulation, Data Collection, Data Preprocessing, Exploratory Data Analysis (EDA), Modeling, and Evaluation and Deployment**—using the well-known Iris dataset to predict flower species. Through hands-on Python and R notebooks, you'll apply familiar concepts like mean, variance, and logistic regression (achieving approximately **93.3% accuracy in Python** and **96.7% in R**) to build a practical predictive model.

This repository includes interactive notebooks, a comprehensive Markdown guide, and a convenient PDF guide, all readily runnable in Google Colab. Whether you're just starting your journey into data science or looking to refresh your fundamental skills, this course aims to make the data science lifecycle accessible, engaging, and easy to understand. Let's dive in and explore the exciting world of data science!

## What You'll Learn

* **Understand the Data Science Lifecycle:** Gain a solid understanding of each phase of the Data Science Lifecycle through practical, real-world examples.
* **Apply Math/Stats Concepts:** Learn how to effectively apply foundational mathematical and statistical concepts (e.g., mean, variance, log-loss) to various data science tasks.
* **Utilize Python and R:** Develop practical skills in using popular data science languages like Python (with libraries such as pandas and scikit-learn) and R (with libraries such as dplyr and nnet) for data preprocessing, insightful data visualization, and building predictive models.
* **Predict Flower Species:** Implement logistic regression to accurately predict Iris flower species and rigorously evaluate the performance of your developed model.

* ## Repository Contents

This repository is organized to provide you with all the necessary resources for a smooth learning experience:

### Notebooks

* [`DS_101_Python.ipynb`](./notebooks/DS_101_Python.ipynb): A comprehensive Python notebook covering all six phases of the Data Science Lifecycle, including the implementation and evaluation of a logistic regression model (achieving approximately 93.3% accuracy). [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/DS101-Lifecycle/blob/main/notebooks/DS_101_Python.ipynb)
* [`DS_101_R.ipynb`](./notebooks/DS_101_R.ipynb): A similar comprehensive notebook implemented in R, covering all six phases of the Data Science Lifecycle, including the implementation and evaluation of a logistic regression model (achieving approximately 96.7% accuracy). [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/DS101-Lifecycle/blob/main/notebooks/DS_101_R.ipynb)

### Guides

* [`data_science_lifecycle.md`](./data_science_lifecycle.md): A detailed Markdown guide explaining each of the Data Science Lifecycle phases in a clear and concise manner.
* [`data_science_lifecycle_notebook_guide.pdf`](./docs/data_science_lifecycle_notebook_guide.pdf): A PDF version of the notebook guide, formatted for easy reading and offline access.
* [`data_science_lifecycle_notebook_guide.tex`](./docs/data_science_lifecycle_notebook_guide.tex): The LaTeX source file for the PDF guide, allowing for customization and modification.

## How to Use This Course

To make the most of this introductory course, we recommend following these steps:

1.  **Read the Guide:** Begin by reading either the [`data_science_lifecycle.md`](./data_science_lifecycle.md) file or the [`data_science_lifecycle_notebook_guide.pdf`](./docs/data_science_lifecycle_notebook_guide.pdf) to gain a foundational understanding of the Data Science Lifecycle and its various phases.
2.  **Run the Notebooks:** Open either [`DS_101_Python.ipynb`](./notebooks/DS_101_Python.ipynb) or [`DS_101_R.ipynb`](./notebooks/DS_101_R.ipynb) directly in Google Colab using the convenient badges provided above. Execute the code cells sequentially to observe the outputs, including insightful scatterplots, predicted probabilities, and the final model accuracy.
3.  **Practice and Experiment:** Enhance your understanding by modifying the provided code. For example, try using sepal length and width instead of petal length and width as predictor variables. This hands-on experimentation will help you build intuition about the data and the modeling process. Additionally, attempt the exercises included in the Markdown guide (e.g., outlining a data science pipeline for predicting house prices).
4.  **Explore Further:** Keep an eye out for future notebooks (e.g., [`DS_102_Linear_Regression_Python.ipynb`](./notebooks/DS_102_Linear_Regression_Python.ipynb)) that will cover other important data science algorithms and techniques.

## Prerequisites

To effectively engage with this course, a basic understanding of the following is recommended:

* **Basic knowledge of mathematics and statistics:** Familiarity with fundamental concepts such as mean, variance, and basic probability is beneficial.
* **Familiarity with Python or R (helpful but not required):** While prior experience with Python or R can be advantageous, the provided notebooks include clear and concise comments to guide beginners through the code.
* **Google Colab account (free):** A free Google Colaboratory account is required to run the interactive notebooks online without the need for local installations.

## Repository Structure

The repository is structured logically to help you navigate the course materials easily:

<pre>
Data_Science_101/
├── notebooks/
│   ├── DS_101_Python.ipynb
│   └── DS_101_R.ipynb
├── docs/
│   ├── data_science_lifecycle_notebook_guide.pdf
│   └── data_science_lifecycle_notebook_guide.tex
├── data_science_lifecycle.md
└── README.md
</pre>

* ## Future Content

This introductory course is continuously evolving. Future content will include algorithm-specific notebooks, starting with implementations of linear regression in both Python ([`DS_102_Linear_Regression_Python.ipynb`](./notebooks/DS_102_Linear_Regression_Python.ipynb)) and R ([`DS_102_Linear_Regression_R.ipynb`](./notebooks/DS_102_Linear_Regression_R.ipynb)). Stay tuned for more hands-on data science tutorials designed to build your skills progressively!

## Contributing

Your feedback and contributions are highly valued! If you have suggestions for improvements, identify any issues, or would like to contribute new content, please feel free to open an issue or submit a pull request on GitHub. Collaborative learning enhances the quality of this resource for everyone.

## License

This course is released under the [MIT License](LICENSE), which means you are free to use, share, and adapt this material with appropriate attribution.

Happy learning, and a warm welcome to your exciting data science journey with **DS101-Lifecycle**!
