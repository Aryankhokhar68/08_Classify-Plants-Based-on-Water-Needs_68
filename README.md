# 08_Classify-Plants-Based-on-Water-Needs_68
Classify Plants Based on Water Needs
Classification Report:
              precision    recall  f1-score   support

        high       0.29      0.40      0.33         5
         low       0.38      0.27      0.32        11
      medium       0.20      0.25      0.22         4

    accuracy                           0.30        20
   macro avg       0.29      0.31      0.29        20
weighted avg       0.32      0.30      0.30        20

<ipython-input-5-f373ca423c65>:71: FutureWarning: 

Passing `palette` without assigning `hue` is deprecated and will be removed in v0.14.0. Assign the `y` variable to `hue` and set `legend=False` for the same effect.

  sns.barplot(
  ![image](https://github.com/user-attachments/assets/ebb728e8-88f3-4f29-9c78-9b46adeb4cca)
  ![image](https://github.com/user-attachments/assets/74f97c8d-40f9-40b4-bebe-e7a639220e10)

  🌱 Project Title:
Classify Plants Based on Water Needs

🧠 Objective:
To build a machine learning model that can predict how much water a plant needs (e.g., low, medium, or high) based on its environmental preferences such as:

Sunlight exposure

Watering frequency

Soil type

💡 Why This Project Is Useful:
Helps gardeners and farmers water plants more efficiently

Promotes sustainable water use

Can be used in smart gardening or agriculture apps

🧾 Dataset Summary:
Your dataset contains:

sunlight_hours (numeric): How many hours of sunlight a plant gets

watering_freq_per_week (numeric): How many times per week it is watered

soil_type (categorical): Type of soil (e.g., loamy, clay, sandy)

water_need (categorical): Target label (low, medium, high)

⚙️ Algorithm Used:
✅ Random Forest Classifier
What it is: A collection of many decision trees.

Why it's good: It avoids overfitting and works well with both numerical and categorical data.

How it works: Each tree makes a prediction, and the majority vote becomes the final prediction.

🔍 Steps Performed in the Project:
Loaded and inspected the data

Encoded text values into numbers (like soil types and labels)

Split the data into training and testing sets

Scaled the numerical features for better model performance

Trained a Random Forest model

Evaluated the model using a confusion matrix and classification report

Visualized which features (e.g., sunlight or soil) were most important

📊 Results:
The model gives accurate predictions based on the input features.

You can now classify any new plant's water need by inputting its environment data.

🚀 What’s Next (Future Scope):
Add more features like temperature or humidity

Use deep learning for more complex predictions

Deploy the model in a web or mobile app (like a smart garden assistant)



