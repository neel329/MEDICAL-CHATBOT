# MEDICAL-CHATBOT
 
## Project Overview

The Medical Chatbot is an intelligent system designed to assist users by processing their medical queries through text or voice input. The system leverages advanced technologies such as Natural Language Processing (NLP), Convolutional Neural Networks (CNN), and speech recognition to provide accurate and context-aware responses. The chatbot is capable of understanding user sentiments, matching input with relevant data, and generating appropriate responses in real-time.

# PROBLEM STATEMENT
India faces challenges in providing quality and affordable healthcare services to its growing 
population. Issues such as lack of transportation, limited availability of doctors, and inadequate 
hospitality facilities hinder the provision of timely and efficient healthcare. This leads to 
delayed treatments, increased mortality rates, and overall healthcare system strain, as 
evidenced during critical situations like the COVID-19 pandemic
Here's a README file tailored to your Medical Chatbot project based on the provided flow structure:

## Features

- **Input Methods**: Supports both text and voice input for user queries.
- **Data Pre-processing**: Efficient pre-processing of input data for accurate analysis.
- **Classification**: Utilizes CNN for classification of medical queries.
- **NLP**: Applies NLP algorithms for symptom recognition, keyword extraction, and statement matching.
- **Multilingual Support**: Supports translation of text input/output to provide responses in the user's preferred language.
- **Interactive GUI**: User-friendly graphical interface for seamless interaction.

## Technologies Used

- **Programming Language**: Python
- **Technologies**: CNN, NLP, Speech Recognition, Text Conversion
- **Dataset**: Medical queries dataset
- **Database**: Knowledge base for medical information
- **User Interface**: Text-based or voice-based input and response
- **Integration**: Joblib model for query processing and response generation

## Software Structure

### 1. GUI Main Page
- **Functionality**: Provides options for voice input and dataset submission.
- **User Flow**: Allows navigation to registration, login, and chat functionalities.

### 2. Registration Page
- **Functionality**: Handles user registration and captures user information for personalized experiences.

### 3. Login Page
- **Functionality**: Authenticates users using their credentials to access chatbot functionalities.

### 4. Chat Page
- **Functionality**: 
  - Displays chat history.
  - Allows users to input queries via text or speech.
  - Processes user input through voice recognition, text conversion, translation, NLP-based matching, and response generation.
  - Interacts with the database to retrieve and store relevant information.

## Code Information Structure

### 1. GUI Main Page Code
- **Responsibilities**: Manages the layout and functionality of the main page, including voice input and dataset submission.

### 2. Registration Page Code
- **Responsibilities**: Manages the user registration process, including secure storage of user information.

### 3. Login Page Code
- **Responsibilities**: Handles user authentication by verifying credentials.

### 4. Chat Page Code
- **Responsibilities**:
  - Manages chat functionality, including voice recognition, text conversion, translation, NLP-based matching, and response generation.
  - Ensures smooth interaction with the database.

## Software Execution Steps

1. **Input as CSV Dataset**: Users can input data as a CSV dataset for processing.
2. **Pre-processing**: The input data is pre-processed to clean and format it for analysis.
3. **Classification**: The pre-processed data is classified using a CNN model.
4. **Apply NLP Algorithm**: NLP algorithms are applied for keyword extraction, matching, and semantic analysis.
5. **Input Methods**: Users can input symptoms or queries by text or speech.
6. **Joblib Model Integration**: The NLP-processed data is analyzed using a Joblib model for generating accurate responses.
7. **Keyword Extraction and Matching**: Keywords are extracted and matched against the database to find relevant information.
8. **Response Generation**: The system generates a response, which is translated if necessary, and displayed to the user in a quick and efficient manner.

## Anaconda Setup

### 1. Install Anaconda
- **Download**: Visit [Anaconda](https://www.anaconda.com/products/individual) and install the appropriate version for your OS.
- **Installation**: Follow the installation instructions for your operating system.

### 2. Create Conda Environment
- **Environment Setup**: Use Anaconda Navigator or the terminal to create a new conda environment specifically for the Medical Chatbot project.

### 3. Install Required Libraries
- **Libraries**: Install required Python libraries such as NLTK, Speech Recognition, PyTorch, scikit-learn, etc.
  ```bash
  conda install <library_name> or pip install <library_name>
  ```

### 4. Set Up Project Structure
- **Directory Setup**: Organize the project into directories for GUI, voice recognition, text conversion, translation, NLP algorithms, and database handling.

### 5. Write and Execute Code
- **Code Implementation**: Write code for the GUI main page, registration page, login page, and chat page. Use appropriate frameworks like Tkinter or PyQt for GUI development.
- **Execution**: Run the application using the main script.

### 6. Test and Debug
- **Testing**: Perform extensive testing of the chatbot system to ensure all modules work as expected.
- **Debugging**: Identify and fix any issues that arise during testing.

## Data Flow Diagram

The flow structure of the system is as follows:

1. **Login**: Users enter their credentials to access the system.
2. **Check Username and Password**: The system verifies the entered credentials.
3. **Successful Login**: If correct, the user is logged in.
4. **Input as Voice or Text**: Users can provide input through voice or text.
5. **Sentiment Analysis**: The system performs sentiment analysis on the input.
6. **Statement Matching**: Keywords are extracted and matched with predefined statements or queries.
7. **Joblib Model Analysis**: The input is analyzed using a CNN-based Joblib model.
8. **Response Generation**: A response is generated and displayed to the user.

By following this structure and design, the Medical Chatbot project can effectively handle various tasks including voice input, dataset recognition, text conversion, translation, NLP-based matching, and response generation, providing users with an interactive and intelligent chatbot experience.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
