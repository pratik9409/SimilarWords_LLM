# LLM Streamlit Application for Finding Similar Texts

Educate Kids is a Streamlit web application designed to help users find similar texts based on their input. It utilizes the OpenAIEmbeddings module to generate embeddings for texts and the FAISS library for efficient similarity search and clustering of large-scale datasets.

### Features:
- **Interactive Interface:** The application provides a user-friendly interface for users to input text and find similar texts.
- **CSV Data Import:** Users can import data from a CSV file for similarity search, making it easy to work with large datasets.
- **Real-time Search:** The application performs similarity search in real-time, providing instant results to the user.


### Setup:
1. Install the required packages:
```bash
pip install streamlit langchain faiss-cpu
```
2. Create a .env file in your project directory and add your OpenAI API key (optional).
3.Run the Streamlit app using the command:
```bash
streamlit run app.py
```

### Usage:
1. Enter your text in the text input field.
2. Click the "Find similar Things" button to find similar texts.
3. The application will display the top matches based on similarity.


### Future Enhancements:
-Incorporate more advanced natural language processing techniques for better similarity matching.
-Enhance the user interface for improved user experience.
-Feel free to explore and contribute to this project to make it more robust and useful for educational purposes.

## EXAMPLE

https://github.com/pratik9409/SimilarWords_LLM/assets/67755812/1cef9b30-cd89-490c-ab87-8d484dd65a55



