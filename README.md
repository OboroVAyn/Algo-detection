# 💰 Fake Banknotes Detection

## Objective
The goal of this project is to build a machine learning model to detect fake banknotes from a given dataset. The dataset includes various features that describe the characteristics of the banknotes, and our objective is to predict whether a given banknote is real or fake.

## Dataset
- 📂 **Dataset**: UCI Machine Learning Repository - Banknote Authentication dataset
- 💳 **Features**: 
  - Variance of wavelet transformed image (continuous)
  - Skewness of wavelet transformed image (continuous)
  - Curtosis of wavelet transformed image (continuous)
  - Entropy of image (continuous)

## Methodology
1. **Data Preprocessing**:
   - Handle missing values (if any) and outliers.
   - Feature scaling to standardize continuous variables.
   
2. **Modeling**:
   - Used **Logistic Regression** for classification.
   - Applied **K-means clustering** to better understand the data distribution.
   
3. **Evaluation**:
   - Evaluated model performance using accuracy, precision, recall, and F1-score.
   - Used a **confusion matrix** to visualize model performance.

## Tools
- **Python**: Pandas, Scikit-learn, Matplotlib
- **Jupyter Notebook**: For detailed analysis and code execution.
- **Machine Learning Algorithms**: Logistic Regression, K-means

## Results
- **Accuracy**: 98.5%
- **Precision**: 97.8%
- **Recall**: 99.1%
- **F1-Score**: 98.4%
- **Confusion Matrix**: The model correctly identified most of the fake notes, with very few false positives.

## How to Run the Code
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/FrankMoukalla/Fake-Banknotes-Detection.git
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook to execute the code:
    ```bash
    jupyter notebook Fake_Banknotes_Detection.ipynb
    ```

## Link to Jupyter Notebook
You can access the full code and analysis in this [Jupyter Notebook](https://github.com/FrankMoukalla/Fake-Banknotes-Detection/blob/main/Fake_Banknotes_Detection.ipynb).

## Conclusion
This project demonstrates how machine learning can be applied to the problem of detecting counterfeit banknotes. By using a simple model like Logistic Regression, we were able to achieve high accuracy and effectively distinguish between real and fake notes.

## Contact Me
- 🔗 [LinkedIn](https://linkedin.com/in/FrankMoukalla)
- 📧 frank.moukallamboka@gmail.com
