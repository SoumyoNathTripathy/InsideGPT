# InsideGPT: A Personal Chatbot
InsideGPT is a personal chatbot application that takes personal data as input and answers questions accordingly. It uses natural language processing and machine learning techniques to understand user queries and generate appropriate responses.

## Getting Started
To run the InsideGPT chatbot application, follow the steps below:

## Prerequisites
Make sure you have the following dependencies installed on your machine:

- Flask
- NLTK
- Keras
- Python

You will also need HTML/CSS and JavaScript knowledge to integrate the frontend with the Flask backend.

## Installation
- Clone the repository to your local machine.

- Open the terminal and navigate to the cloned repository.

- Install the dependencies by running the following command:

Copy code:
```
pip install -r requirements.txt

```

## Usage
- To start the InsideGPT chatbot application, follow the steps below:

- Open the terminal and navigate to the cloned repository.

Run the following command:
```
python app.py

```
- Open your web browser and navigate to http://127.0.0.1:5000/.

- Type your questions or queries into the chatbot interface and press Enter.

- The chatbot will process your query and generate an appropriate response.

## How it Works
The InsideGPT chatbot application uses a pre-trained neural network model to predict the intent of user messages and generate responses accordingly. The model is trained using a JSON file named "intents.json" which contains information about various intents and their associated patterns and responses.

The application uses the Natural Language Toolkit (NLTK) library to tokenize and lemmatize user messages and a bag-of-words model to represent them as input for the neural network. The chatbot's responses are generated based on a set of predefined intents and responses defined in the "intents.json" file.

## Demo ScreenShots of the UI:
1. ![image](https://user-images.githubusercontent.com/85414445/232205669-c9587bb3-bb5e-4db9-9083-7cb9067ccd40.png)
2. ![image](https://user-images.githubusercontent.com/85414445/232205691-a72daa4b-5437-47b0-b664-22d17c2fd812.png)
3. ![image](https://user-images.githubusercontent.com/85414445/232205713-9c2e7325-917c-4198-96b5-8dd5b057a097.png)


## Contributing
If you find any issues or bugs in the InsideGPT chatbot application, feel free to open an issue or submit a pull request. We welcome contributions from the community.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
