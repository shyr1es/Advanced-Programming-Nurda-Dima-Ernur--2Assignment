# LLM Chat Application with Large Language Models

This project is a web application built with Streamlit, integrated with ChromaDB to store chat history, and uses the Ollama language model (LLM) to process user queries. The app provides an intuitive interface for sending queries and receiving instant responses from a language model.

## Key Features
- **Document Upload**:
  - Users can upload one or more `.txt` files containing relevant information.
  - The content of these files is stored in ChromaDB for contextual question-answering.
- **Interactive Chat**:
  - Submit questions and receive real-time responses based on uploaded documents.
  - If no relevant context is found in the documents, the LLM will provide a generic answer.
- **LLM Integration**:
  - The app integrates with the Ollama LLM (`llama3.2`) for advanced query processing.
- **Context-Based Responses**:
  - Questions are matched with the content of the uploaded documents to ensure accurate and relevant answers.
- **Chat History**:
  - All user queries and LLM responses are stored in ChromaDB and can be reviewed at any time.
- **Intuitive Interface**:
  - Built with Streamlit, the app offers a clean, user-friendly interface.

---

### Requirements
To run this application on your local machine, you will need to install the following Python packages:

- streamlit
- chromadb
- langchain-ollama
- os (this is part of the Python standard library)

You can install all dependencies with the following command:
```bash
pip install -r requirements.txt
```
Alternatively, you can manually install each package:
```bash
pip install streamlit chromadb langchain-ollama
```
### Setup
### Clone the Repository:
You can clone the repository from GitHub:
```bash
git clone https://github.com/shyr1es/Advanced-Programming-Nurda-Dima-Ernur--2Assignment.git
cd Advanced-Programming-Nurda-Dima-Ernur-
```
### Install Dependencies:
After cloning the repository, navigate to the project directory and install the dependencies:
```bash
pip install -r requirements.txt
```
### Run the Streamlit App:
To start the application, run the following command:
```bash
streamlit run app.py
```

### Using the App:
Open the app in your browser (usually at http://localhost:8501).
Enter a query in the text input field.
Press "Submit" to send the query to the LLM and receive a response.
Both the query and the response will be saved in ChromaDB for future reference.

### Terminal Feedback:
The terminal will show messages indicating that the query and response have been successfully saved in the database.


### Example of How It Works
![image](https://github.com/user-attachments/assets/1e87b333-0013-4403-a6f1-687e3e8a7672)
![image](https://github.com/user-attachments/assets/e77e6704-7b53-492e-aa04-7758b26d1b65)
![image](https://github.com/user-attachments/assets/8b8ac4de-7953-40ee-a910-221db33a40b6)
![image](https://github.com/user-attachments/assets/3289b6a8-3166-4dd2-9e4e-4be654615565)



