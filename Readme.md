# Text Summarization App

This is a web application for text summarization using various NLP techniques. The app leverages libraries such as SpaCy, NLTK, and Sumy to provide different summarization methods.

## Features

- **SpaCy Summarization**: Uses SpaCy for text summarization.
- **NLTK Summarization**: Uses NLTK for text summarization.
- **Sumy Summarization**: Uses Sumy with the LexRank algorithm for text summarization.
- **Web Scraping**: Extracts text from web pages for summarization.

## Installation

1. **Clone the repository**:
    OR 
    **Download the Code**
    ```sh
    cd text-summarization-app
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    ```

3. **Activate the virtual environment**:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```

4. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

5. **Download SpaCy model**:
    ```sh
    python -m spacy download en_core_web_sm
    ```

## Usage

1. **Run the application**:
    ```sh
    python app.py
    ```

2. **Open your web browser** and go to `http://127.0.0.1:5000/`.

3. **Enter the text** you want to summarize or provide a URL for web scraping.

4. **Choose the summarization method** (SpaCy, NLTK, or Sumy) and click on the "Summarize" button.

## Screenshots:
![Home](https://github.com/Rayyan9477/Text-Summarization-App/blob/main/images/1.png)


![Output](https://github.com/Rayyan9477/Text-Summarization-App/blob/main/images/2.png)

![Stats](https://github.com/Rayyan9477/Text-Summarization-App/blob/main/images/4.png)

## File Structure

- `app.py`: The main Flask application file.
- `templates/`: Contains the HTML templates for the web app.
- `static/`: Contains static files like CSS and JavaScript.
- `requirements.txt`: Lists the Python dependencies for the project.

## Dependencies

- Flask
- SpaCy
- NLTK
- Sumy
- BeautifulSoup4

## Connect With Me

- **[LinkedIn](https://www.linkedin.com/in/rayyan-ahmed9477/)**
- **[GitHub](https://github.com/Rayyan9477)**

