# Book Recommendation Algorithm Project

This repository contains the implementation of a book recommendation algorithm using K-Nearest Neighbors (KNN). The project utilizes the Book-Crossings dataset to develop a model that recommends books similar to a given book title.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)


## Overview

The goal of this project is to create a book recommendation system using the KNN algorithm. After cleaning and processing the dataset, the NearestNeighbors model from the `sklearn.neighbors` package is used to find and recommend books similar to a given book based on user ratings.

## Dataset

The dataset used in this project is sourced from FreeCodeCamp and consists of:
- `BX-Books.csv`: Contains book information (ISBN, title, author)
- `BX-Book-Ratings.csv`: Contains user ratings for books (user, ISBN, rating)

## Project Structure

```
book-recommendation-algorithm/
│
├── notebooks/
│   └── book_recommendation.ipynb    # Jupyter notebook for the project
│
├── data/
│   ├── BX-Books.csv                 # Book data
│   └── BX-Book-Ratings.csv          # Ratings data
│
├── README.md                        # Project README file
│
└── requirements.txt                 # Required Python packages
```

## Installation

To run this project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/book-recommendation-algorithm.git
   cd book-recommendation-algorithm
   ```

2. **Set up the environment:**
   - It is recommended to use a virtual environment to manage dependencies. You can create one using `venv` or `conda`.

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Open the Jupyter Notebook:**
   - Navigate to the `notebooks` directory and open `book_recommendation.ipynb` using Jupyter Notebook or Google Colaboratory.

2. **Run the notebook:**
   - Follow the instructions in the notebook to download the dataset, clean the data, train the model, and generate book recommendations.

3. **Get book recommendations:**
   - Use the `get_recommends` function to get a list of similar books for a given book title.

