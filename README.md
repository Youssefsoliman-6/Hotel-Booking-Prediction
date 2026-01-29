# Hotel Booking Cancellation Prediction 🏨

## 📌 Project Overview
This project implements a complete machine learning pipeline to predict whether a hotel booking will be canceled. By analyzing customer behavior and booking details, the system helps hotels minimize revenue loss and optimize room availability.

The project features advanced **Feature Selection using Genetic Algorithms (GA)** to optimize model performance.

## 📂 Repository Structure
* **`final_hotel_bookings_ai_poroject.ipynb`**: The main Jupyter Notebook containing the code for EDA, Preprocessing, GA, and Modeling.
* **`data/`**: Contains the `hotel_bookings.csv` dataset.
* **`docs/`**: Includes the detailed project report (`AI Project Doc..docx`).

## 🛠️ Project Workflow
1.  **Data Preprocessing:** Handling missing values, label encoding, and data balancing.
2.  **Exploratory Data Analysis (EDA):** Analyzing correlations between lead time, market segments, and cancellations.
3.  **🧬 Feature Selection (Genetic Algorithm):** Implemented a Genetic Algorithm to select the most relevant features, reducing dimensionality and improving model efficiency.
4.  **Model Training:**
    * **K-Nearest Neighbors (KNN)**
    * **Decision Tree Classifier**
    * **Multi-Layer Perceptron (MLP) Neural Network**
5.  **Evaluation:** Models were evaluated using Accuracy, Precision, Recall, F1-Score, and Confusion Matrices.

## 🏆 Results
The **MLP Classifier** demonstrated the best overall performance among the tested models, particularly in terms of Recall and F1-Score, making it the most suitable choice for identifying potential cancellations.

## 🚀 How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/Hotel-Booking-Prediction.git](https://github.com/YOUR_USERNAME/Hotel-Booking-Prediction.git)
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Run the notebook:
    ```bash
    jupyter notebook final_hotel_bookings_ai_poroject.ipynb
    ```

## 👥 Authors
* **Youssef Ahmed** 
