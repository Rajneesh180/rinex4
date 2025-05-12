# SPAM-HAM CLASSIFIER 📨🚫

This is a simple web application built using **Streamlit** for classifying whether a given message is **SPAM** or **HAM** (non-SPAM). The classifier is based on a pre-trained model that uses machine learning to predict whether a message is spam or not.

## Project Overview 🎯

This project utilizes a machine learning model that was trained on a dataset containing labeled SPAM and HAM messages. The model is then used in a web app where users can input text and receive predictions about whether the message is spam or not.

### Key Features ⚡:

* **Input:** A text input where users can enter a message.
* **Output:** A prediction indicating whether the message is **SPAM** or **HAM**.
* **Streamlit:** The web interface is created using Streamlit, making it easy to interact with the model in real-time.

## Technologies Used 🛠️

* **Python** 🐍
* **Streamlit** for the web interface 💻
* **Joblib** to load the pre-trained machine learning model 📦
* **Machine Learning Model** for SPAM-HAM classification (the model used is pre-trained and loaded from a `.joblib` file) 🧠

## How to Run 🚀

1. **Clone this repository** to your local machine:

   ```bash
   git clone <repository-url>
   ```

2. **Install the required dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

   (Make sure you have **Streamlit** and **joblib** installed along with any other necessary libraries.)

3. **Load your pre-trained model** into the application. The model should be a file named `spam-ham.joblib`. If it's not available, you will need to train a model and save it with the appropriate name using **joblib**.

4. **Run the Streamlit app**:

   ```bash
   streamlit run app.py
   ```

5. Visit the provided link (typically `http://localhost:8501`) in your browser to interact with the app.

## How it Works 🔍

* The user enters a message in the input field.
* Once the **Predict** button is clicked, the app uses the pre-trained machine learning model to classify the message as **SPAM** or **HAM**.
* The prediction is displayed on the screen.

## Sample Usage ✍️

1. **Enter a message**:
   Example input: "Congratulations, you have won a lottery!"

2. **Click the "Predict" button** to see the result.

   Example output: "SPAM" 🚫

## Notes 📝

* The quality of predictions depends on the dataset used to train the model.
* The current application assumes that the model (`spam-ham.joblib`) is available and correctly trained.

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
