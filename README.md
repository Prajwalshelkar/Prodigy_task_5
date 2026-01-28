# 🍔 Task 5: Food Recognition & Calorie Estimation

*Prodigy Infotech Internship - Machine Learning Track*

### 📌 Project Overview
This project develops a model to *recognize food items* from images and *estimate their calorie content*.

To demonstrate the functionality efficiently, the model is trained on a subset of the *Food-101* dataset, focusing on specific classes (e.g., Pizza, Hamburger, Ice Cream). Once the image is classified, the system maps the result to a nutritional database to provide a calorie estimate.

### 📊 Model Output
The system correctly identifies the food item and retrieves the corresponding calorie count.

<img width="1101" height="801" alt="image" src="https://github.com/user-attachments/assets/733ad92d-00dd-4eb5-8996-93e6b9f9f2ad" />


### 🛠 Technologies Used
* *Python*
* *TensorFlow / Keras* (CNN Model)
* *Matplotlib* (Visualization)
* *NumPy*

### 📂 Dataset
* *Source:* [Food-101 (Kaggle)](https://www.kaggle.com/dansbecker/food-101)
* *Implementation:* Used a TensorFlow subset (10_food_classes_all_data) to optimize training time and resource usage in Google Colab.

### 🚀 How to Run
1.  Open PRODIGY_ML_05.ipynb in Google Colab.
2.  Run the cells to download the dataset and train the model.
3.  The final cell picks a random test image and displays the prediction + estimated calories.
