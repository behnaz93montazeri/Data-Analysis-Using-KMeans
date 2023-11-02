# Data-Analysis-Using-KMeans

This project explores the application of the K-Means clustering algorithm on two different datasets. The goal is to assess the performance of K-Means in both scenarios, one involving synthetic data and the other using real-world data on colleges categorized as private or public.

## Project Structure

- `project1/`: First project using synthetic datasets.
- `project2/`: Second project using real college data.
- `README.md`: This file providing an overview of the project.

## Project 1 - Synthetic Dataset

In the first project, we generated synthetic data using scikit-learn and applied K-Means clustering to investigate its effectiveness. The key steps include:

1. Generating synthetic data.
2. Applying K-Means clustering to the synthetic dataset.
3. Comparing the K-Means results with the original data.

The findings indicate that K-Means works effectively and can successfully cluster the data.

## Project 2 - Real College Dataset

In the second project, we used a real dataset containing information about colleges, including whether they are private or public. The primary steps for this project include:

1. Loading the real college dataset.
2. Performing exploratory data analysis (EDA) and visualizing the patterns between private and public schools.
3. Applying K-Means clustering to the dataset (the label column, Private, has been dropped).

While the dataset contains numerous features, the challenge is visualizing and interpreting the results effectively. Therefore, we created scatter plots to compare K-Means clustering with the original data, which showed promising results.

## Usage

- (`project1/` and `project2/`) are both in a same Jupyter Notebook (KMeans Clustering Project.ipynb) with code and comments explaining the workflow.
- make sure that you put the dataset (College_Data) in the same directory as the Jupyter Notebook is.

- Feel free to explore the code, data, and results within each project directory.

## Dependencies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

## Conclusion

In summary, this project highlights the application of K-Means clustering in two distinct scenarios. The first project demonstrates K-Means' effectiveness on synthetic data, while the second project showcases the challenges of applying it to a real-world dataset with many features.

The scatter plots included in the second project visually confirm the effect of K-Means in clustering the data, even though the results may not be readily interpretable due to the high dimensionality of the dataset.
