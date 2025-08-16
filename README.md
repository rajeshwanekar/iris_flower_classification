# 🌸 Iris Flower Classification

This project demonstrates **Iris flower classification** using machine learning. It uses the classic **Iris dataset** (sepal length, sepal width, petal length, petal width) to classify iris species: Setosa, Versicolor, Virginica.

***

## 📂 Structure

- `iris_flower_classification.ipynb` – Main notebook with code, visualizations, and model results.
- `README.md` – Project documentation (this file).
- `img/` – Folder for images/screenshots (add your saved images here).

***

## 📊 Sample Visualizations

Below are some example plots generated during the EDA and model analysis.

### Dataset First Rows

- Loads Iris dataset (scikit-learn)
- DataFrame conversion & exploration
- Data visualization (pairplot, scatterplot, boxplot)
- Support Vector Classifier (SVC) training & hyperparameter tuning (GridSearchCV)
- Classification accuracy evaluation

***

## 🛠️ Requirements

```bash
pip install pandas scikit-learn matplotlib seaborn
```

***

## 🚀 Usage

1. Download or clone this repository.
2. Open `iris_flower_classification.ipynb` in Jupyter Notebook or Colab.
3. Run each cell to see results and visualizations.
4. To save plots as images for README, use `plt.savefig('img/your_plot.png')` in your code after each plot.

***

## 📑 Dataset

- **Features:** sepal length (cm), sepal width (cm), petal length (cm), petal width (cm)
- **Target Classes:** Setosa, Versicolor, Virginica

***

## 📈 Example Results

- Best SVM model parameters via GridSearchCV.
- Achieved test accuracy: ~95%.
- Plots reveal clear separability between Setosa and other species, with Versicolor and Virginica showing overlap.

***


## 📜 License

This project is for educational/demo use.
