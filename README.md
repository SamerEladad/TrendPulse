# TrendPulse

Welcome to TrendPulse, a deep learning and product recommendation project designed as a sandbox for experimentation and innovation. This prototype is just the beginning, intended as a playground where you can explore new ideas, try different approaches, and learn from our experiences. Whether you’re a seasoned developer or a curious learner, there’s something valuable here for everyone. Let’s dive in and discover what we can achieve together!

## Table of Contents
- [TrendPulse](#trendpulse)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Project Scope](#project-scope)
  - [Methodology](#methodology)
  - [Challenges and Solutions](#challenges-and-solutions)
  - [Results](#results)
  - [Learnings](#learnings)
  - [Technologies Used](#technologies-used)
  - [Folder Structure](#folder-structure)
  - [Installation](#installation)

## Project Overview
We developed TrendPulse to harness the capabilities of deep neural networks in assisting dropshippers with product research. Users input specific criteria, and the model processes this information to offer five tailored product recommendations. This tool is particularly designed for beginner to intermediate dropshippers.

## Project Scope
This project aims to develop a prototype recommendation system using deep neural networks to assist dropshippers in product research. The key components of the project include:

- **Dataset**: Utilization of a Kaggle dataset focusing on 12 dropshipping categories.
- **Neural Network**: A model with five fully connected layers that predicts product ratings and ranks products based on user inputs.
- **User Interaction**: A simple interface where users input criteria like category and price to receive product recommendations.

## Methodology

### Initial Approach
We initially attempted to scrape data from online marketplaces but faced significant limitations, leading us to use a Kaggle dataset. This allowed us to focus on developing a neural network prototype.

### Neural Network Development
The selected Kaggle dataset was cleaned, reduced, and stratified into training, validation, and test sets. The neural network comprises five fully connected layers, with inputs including category, rating, number of ratings, and price. The model predicts product rating classes and ranks the products within these classes.

## Challenges and Solutions

### Challenges
- **Data Scraping**: The process was time-consuming and restricted by marketplace limitations.
- **Model Overfitting**: Overfitting occurred due to an excessive number of product classes.
- **Class Imbalance**: We encountered issues with class imbalance during model training.

### Solutions
- **Data Utilization**: We adopted a Kaggle dataset to circumvent scraping challenges.
- **Overfitting Mitigation**: Clustering ratings into three balanced classes was implemented to address overfitting.
- **Class Balance**: A three-class system was employed to improve model performance and address class imbalance.

## Results
The developed neural network serves as a prototype capable of predicting and suggesting the top 5 products within a specific class. While this is a simplified model, it provides a solid foundation for future enhancements, potentially expanding into a more sophisticated recommendation system.

## Learnings
- **Teamwork**: Effective communication and realistic expectation-setting were crucial.
- **Technical Insights**: Scraping large datasets and understanding APIs require careful planning and project scope adjustment.
- **Leveraging LLMs**: Large Language Models have immense potential. This project provided foundational insights into using LLMs in practical scenarios, paving the way for future implementations.

## Libraries Used
- **Programming Languages**: Python
- **Libraries**:
  - `pandas`, `numpy`: Data manipulation and analysis.
  - `sklearn`: Model evaluation, data preprocessing.
  - `torch`, `torch.nn`, `torch.optim`, `torch.utils.data`: Neural network development and training.
  - `pickle`: Serialization.
  - `os`, `time`: System operations and timing functions.
- **Development Tools**: Jupyter Notebook for experimentation and prototyping.

## Folder Structure

- **data/**: Contains data files used in the project.
  - **datasets.ipynb**: Notebook for dataset handling.
  - ...

- **notebooks/**: Jupyter notebooks for analysis and prototyping.
  - **submission/**: Contains the key project notebook.
    - **TrendPulse.ipynb**: Main notebook containing the core parts of the project.
  - ...

- **README.md**: Project documentation.
- **.gitignore**: Specifies files and directories to ignore in version control.
- ...

## Installation
To set up TrendPulse on your local machine, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/SamerEladad/TrendPulse.git
   cd TrendPulse

## Contributors

- **Dilara Bursa**: [LinkedIn](https://www.linkedin.com/in/dilara-bursa-a80b8b22a)
- **Muhammad Uzair Rana**: [LinkedIn](https://www.linkedin.com/in/muhammad-uzair-rana-9b63b455/)
- **Samer Eladad**: [LinkedIn](https://www.linkedin.com/in/samereladad/)
