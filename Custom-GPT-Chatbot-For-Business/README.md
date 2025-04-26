## About This Project
This project is a design of Custom GPT Chatbot that is used in multiple domains. This chatbot can be confugured and customized for specific application like education, business, customer service and much more.
Moreover tis project is developed at comericial level for a client and sold with some extra services and utilities. 

## Project Explanation:
The Project hereafter refered to as BlenderBot Chatbot is a conversational AI application that enables users to interact with a chatbot powered by the facebook/blenderbot-400M-distill model from Hugging Face. It provides both a command-line interface (CLI) and a web-based interface built with Flask, allowing users to engage in natural language conversations. The project showcases how to integrate a pre-trained transformer model into a user-friendly application for dialogue generation.


 * **What it is:** A Python-based chatbot leveraging a pre-trained conversational model to simulate human-like interactions, accessible via CLI or a web browser.


 * **What it does:** Responds to user inputs with context-aware replies, maintains a limited conversation history to ensure coherent dialogues, and provides an intuitive web interface for seamless interaction.




 * **How it does it:** Utilizes the Hugging Face Transformers library to load the BlenderBot model and tokenizer, processes user inputs with proper tokenization and history management, generates responses using beam search, and serves the web interface through Flask with HTML/CSS for styling.

## Technologies
- **Python 3.8+**: Programming language.
- **Hugging Face Transformers**: For loading and using the BlenderBot model and tokenizer.
- **Flask**: Web framework for the frontend.
- **HTML/CSS**: For rendering the web interface.





## Usage

1. **Run the Flask application**:
   ```bash
   python app.py
   ```
   - The app will start on `http://127.0.0.1:5000`.

2. **Access the chatbot**:
   - Open a browser and navigate to `http://127.0.0.1:5000`.
   - Enter your message in the input field and submit to interact with the chatbot.
   - The chatbot maintains a conversation history (limited to 3 turns by default) and responds based on the input.

3. **Run the CLI version** (optional):
   ```bash
   python chatbot.py
   ```
   - Interact with the chatbot via the command line by typing messages.
   - Type `quit` to exit.

## Features
- Interactive chatbot powered by `facebook/blenderbot-400M-distill`.
- Maintains conversation history with a limit to prevent token overflow.
- Web interface built with Flask for easy user interaction.
- Configurable generation parameters for response quality.
- Error handling for robust operation.


## About The Author:


This project is  created by Faizan Saleem Siddiqui, a passionate developer with an interest in natural language processing and Artificial Intelligence. With a background in Python programming and machine learning, they enjoy building AI-driven applications that make technology accessible and engaging. 
Faizan Saleem Siddiqui is  an M. Phil Research Scholar, a freelaner and Visiting Faculty Member at Quaid-i-Azam University Islamabad. He has working in the filed of Artificial Intelligenece since last 2 years as a freelancer as well as researcher. There are more than 10 industrial & Comercial Projects at his credit. 
Learn more about me here on my LinkedIn
[LinkedIn Profile](https://www.linkedin.com/in/faizan-saleem-siddiqui-4411bb247/)


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



































