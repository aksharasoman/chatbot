
# Order-Bot for a Pizza Restaurant using (free) Gemini LLM API 🍕🤖
Welcome to the Order-Bot repository, a pizza restaurant chatbot designed to streamline customer orders. 

This repository contains implementation of a Chatbot based on **Gemini 1.5 Flash LLM**. A user-friendly GUI is built using opensource python library called **Panel**.

### Getting Started
1. Clone the repository:
```
git clone https://github.com/aksharasoman/order-bot.git
```

2. Navigate to the project directory

3. Install dependencies:
```
pip install -r requirements.txt
```
4. Deploy the chatbot locally::
``` 
panel serve v2_gemini-pizza-chatbot_chatInterface.ipynb --autoreload
```
  Click on the generated url to open the chatbot in your browser.

5. Interact with the bot through the GUI.
  

### Files' Description:
Main File: v2_gemini-pizza-chatbot_chatInterface.ipynb

- **v1_gemini-pizza-chatbot.ipynb** 
  - In this notebook, we are building a chatbot using *free*-version of Gemini API.
  -  The GUI is built using the open-source Python library Panel.
  -  The chat bot is an *OrderBot*, an automated service to collect orders for a pizza restaurant. 
- **v2_gemini-pizza-chatbot_chatInterface.ipynb** 
  - Similar to the previous notebook, but with an improved GUI using the 'ChatInterface' component of the Panel library.
  
- **chatgpt-chatbot_dlai.ipynb**  
  - As a first step, I used this notebook to familiarize myself with the fundamental concepts of a chatbot.
  - In this notebook, you will explore how you can utilize the chat format to have extended conversations with chatbots personalized or specialized for specific tasks or behaviors.
  - This notebook is downloaded from the deeplearning.ai course: "[ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)" (chapter: chatbot). 
  - Here, the chatbot is built using OpenAI API (Paid subscription required).
  - The GUI is built using the open-source Python library Panel.

- requirements.txt
  - lists all the necessary Python packages and their versions needed to run the project.
  
- pizzabot_chatInterface.zip
  - The zip folder is to be uploaded to [Ploomber Cloud](https://platform.ploomber.io/) for free deployment of the chatbot. More details about this deployment and other deployment options can be found in my blog post.

- **v2_pizzabot_screenRecording.mov**
  - A video of our OrderBot in action.
  
### Further information
Visit my blog.
