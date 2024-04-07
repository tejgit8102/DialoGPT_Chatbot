# ChatBot

## Installation & Setup

[Install Python] https://www.dataquest.io/blog/installing-python-on-mac/

[Install pip] https://phoenixnap.com/kb/install-pip-mac

If you have Python & pip installed then check their version in the terminal or command line tools

```
python3 --version
```

```
pip --version
```

## Installing Flask

In your terminal run the requirements.txt file using this pip

```
pip install -r requirements.txt
```

## What you will create

In this project, I have built a chatbot using Microsoft DialoGPT, a pre-trained language model capable of generating human-like responses. The chatbot communicates with users via a web interface created using Flask, a Python web framework, and HTML, CSS, and JavaScript for the frontend.

Here's what I have accomplished in this project:

1. **Integration of DialoGPT with Flask**: I integrated the DialoGPT model with Flask to create a backend server capable of processing user inputs and generating responses.

2. **Frontend Development**: I created a visually appealing and interactive chat interface using HTML, CSS, and JavaScript. The frontend allows users to input messages and displays responses from the chatbot in real-time.

3. **Handling HTTP Requests**: I used jQuery to handle HTTP requests between the frontend and backend servers. This enables seamless communication between the user's browser and the Flask application.

4. **Model Deployment**: I deployed the Flask application to make it accessible to users over the internet. Users can interact with the chatbot by accessing the web interface through their web browsers.

5. **Training and Fine-tuning the Model**: While not explicitly mentioned in the script, I may have trained or fine-tuned the DialoGPT model to improve the accuracy of its responses. This step would involve providing the model with additional training data or fine-tuning its parameters to better suit the specific use case of the chatbot.

Overall, this project demonstrates how to build a fully functional chatbot capable of engaging in conversations with users using natural language processing techniques and web development technologies.

# ChatBot Link
The Chatbot is constructed using the Microsoft/DialoGPT-medium model.

```
https://huggingface.co/microsoft/DialoGPT-medium
```

# User-Html

```
var userHtml = '<div class="d-flex justify-content-end mb-4"><div class="msg_cotainer_send">' + user_input + '<span class="msg_time_send">'+ time + 
    '</span></div><div class="img_cont_msg"><img src="https://i.ibb.co/d5b84Xw/Untitled-design.png" class="rounded-circle user_img_msg"></div></div>';
```

# Bot-HTML

```
var botHtml = '<div class="d-flex justify-content-start mb-4"><div class="img_cont_msg"><img src="https://i.ibb.co/fSNP7Rz/icons8-chatgpt-512.png" class="rounded-circle user_img_msg"></div><div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></div></div>';
```