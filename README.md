This repository contains implementation of a Chatbot based on Gemini Flash LLM. The GUI is built using opensource python library called Panel.

### To deploy the chatbot locally:
Run this in the command-line:

```panel serve v2_gemini-pizza-chatbot_chatInterface.ipynb --autoreload```

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
