User Guide for MBTI Predictor Web App

This guide will walk you through the steps to execute and use the MBTI Predictor web application.

Step 1: Installation

Ensure you have Python installed on your system. You can download Python from the official website: Python Downloads.
Install Flask and other required libraries by running the following command in your terminal or command prompt:
Copy code
pip install flask scikit-learn matplotlib wordcloud
Step 2: Download the Application Files

Download the following files:
app.py: Backend Python script for the Flask application.
index.html: Frontend HTML file for the user interface.
mbti.csv: CSV file containing the MBTI dataset.
mbti_nlp_model.pkl: Pre-trained NLP model for predicting MBTI types.
Step 3: Run the Application

Open a terminal or command prompt.
Navigate to the directory where you saved the downloaded files.
Run the Flask application by executing the following command:
Copy code
python app.py
Once the Flask application is running, you should see a message indicating that the server is running. By default, the application will be accessible at http://127.0.0.1:8080/.
Step 4: Using the Application

Open a web browser and navigate to http://127.0.0.1:8080/ (or whichever URL is indicated in your terminal).
You will see the home page of the MBTI Predictor web application.
Enter a comment or text in the input field labeled "Enter your comment".
Click on the "Predict" button to predict the MBTI type based on the input text.
The predicted MBTI type will be displayed along with the accuracy of the prediction.
Additionally, you can click on the icons in the navigation bar to view different visualizations:
Distribution: Shows the distribution of MBTI types.
Word Cloud: Displays word clouds for each MBTI type.
Post Lengths: Shows the average post length for each MBTI type.
Step 5: Interacting with Visualizations

Click on the respective icons in the navigation bar to view different visualizations.
The visualizations will be updated dynamically without the need to reload the page.
Step 6: Exiting the Application

To stop the Flask application, press Ctrl + C in the terminal or command prompt where it is running.
That's it! You've successfully executed and used the MBTI Predictor web application. If you encounter any issues or have any questions, feel free to reach out for assistance.

![image](https://github.com/johncrescenzi/capstone/assets/12722829/b938ec39-612a-4288-bcc4-4be4f83eb71c)

![image](https://github.com/johncrescenzi/capstone/assets/12722829/3bfcbffc-c94f-49e5-8d6c-afd9d33024e0)

![image](https://github.com/johncrescenzi/capstone/assets/12722829/487ad81a-6f5a-4dd6-9cca-7c203b2ffb94)
