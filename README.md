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
git clone https://github.com/shyr1es/Advanced-Programming-Nurda-Dima-Ernur-.git
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
![image](https://github.com/user-attachments/assets/4173a8b9-2bc3-4f41-940f-4f01957a37bd)


### Example of How It Works
User Query: "What is the weather like today?"
Model Response: "I don't have access to live data, but you can check the weather online."
![image](https://github.com/user-attachments/assets/bf6794d2-030d-43ea-9e73-30326e0178da)

Saved in ChromaDB: Both the user query and the response are stored in the database.
