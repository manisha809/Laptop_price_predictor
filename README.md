# Laptop_price_predictor

#About Project:

Objective: This project aims to predict the price of a laptop based on various features such as brand, type, RAM, weight, touchscreen availability, IPS display, screen size, resolution, CPU, HDD and SSD storage, GPU, and operating system.

Technologies Used: The project utilizes Streamlit, a Python library for creating web applications, to create an interactive user interface for predicting laptop prices. The machine learning model for prediction is loaded using the pickle library.

User Interface: The user interface provides input options for the user to select laptop features, including brand, type, RAM, weight, touchscreen availability, IPS display, screen size, resolution, CPU, HDD, SSD, GPU, and operating system. The prediction is triggered by clicking the "Predict Price" button.

Prediction Logic: The project incorporates a machine learning pipeline (pipe) and a preprocessed DataFrame (df) to make predictions. The selected features are processed and passed through the model to predict the laptop price.

Output: Upon clicking the "Predict Price" button, the predicted price for the configured laptop is displayed on the interface. The price is presented in Indian Rupees (₹), and it is calculated using the exponential of the predicted value from the machine learning model.

Application Demo:https://laptoppricepredictor-ehekuefwobldrkpdo3thvm.streamlit.app/
