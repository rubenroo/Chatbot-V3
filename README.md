# Chatbot-V3
For the Minor Real Fake, Real Impact, I created a chatbot with Python. This chatbot is built with NLTK, TensorFlow, and neural networks. It is highly customizable and can be modified to suit your needs. This chatbot was made with a tutorial from [pycodemates.com.](https://www.pycodemates.com/2021/11/build-a-AI-chatbot-using-python-and-deep-learning.html) 


**Test the bot:**
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rubenroo/Chatbot-V3/HEAD?labpath=chatbot%20versie%205%20(feb%2C%20ruben).ipynb)





# Applied my learnings
**Used Literature**

I've added several features that give the chatbot 'trust and engagement' design features according to the literature. I have used this paper: *The Effect of Design Features on Relationship Quality with Embodied Conversational Agents: A Systematic Review* [(link)](https://link.springer.com/article/10.1007/s12369-020-00680-7) I took the following insights from this and applied them to the chatbot:


- *Language features that were shown to improve closeness included humour, a first-person storytelling perspective, ‘social reason- ing’ language (including self-disclosure, acknowledgement, praise, reference to shared experiences*
  - I added humour and a personality through emoticons, jokes and funny sayings

  
- *Small talk was shown to improve perceived trust, knowledge of the user, and success of the interaction for extroverted users, while task-oriented talk received higher ratings from introverted users*
  - If you ask the chatbot how he's doing, he also asks right away how you're doing. This is to  improve perceived trust.
  
- *Self-disclosure of humanlike back stories was associated with higher self- disclosure intimacy and amount for users high in anxiety. ECAs with a first-person storytelling perspective were shown to elicit more self-disclosure from users com- pared to ECAs with a third-person storytelling perspective*
-*mpathic language and facial expressions were shown to improve trust, ratings of agent caring and feelings of support*
   - I added the first-person narrative perspective by having the chatbot talk about his hobbies and let him tel a personal story.



**CDI course**

I also applied on the knowledge gained from the AI trainer course from [conversationdesigninstitute.com.](conversationdesigninstitute.com) i've used the following insight in this chatbot:
- Generally, 20 training phrases do you want to match to an intent
  - I noticed that the chatbot started responding worse by adding 20 patterns per intent. Nevertheless, I applied this because it shows that I understand the lessons from the course. 
- If the confidence score is low, the Assistant should not offer the user an intent

- You have to get the postive flow right first
  -I've tested the positive flow






# How it works
chatbot built with NLTK, TensorFlow, and neural networks is a type of artificial intelligence program that is designed to simulate conversation with human users through natural language processing techniques. NLTK (Natural Language Toolkit) is a Python library that provides tools for processing and analyzing natural language data, such as text and speech. TensorFlow is an open-source machine learning library that can be used to build and train neural networks. Neural networks are a type of machine learning model that are inspired by the structure and function of the human brain, and are commonly used for tasks such as image and speech recognition, natural language processing, and decision-making. Together, these tools and technologies can be used to create a chatbot that can understand and respond to natural language input from users in a human-like manner. (this paragraph is generated with chatGPT)

# What the chatbot can do
The chatbot demonstrates the techniques mentioned above. The following questions are possible:

- Say Hello (Hi there)
- Ask how the chatbot is doing (How are you doing?)
- Say goodbye (See you later)
- Thank him (Thanks)
- check his check_wellbeing (Are you okay?)
- Ask the chatbot for a joke (Tell me a joke)
- Ask for his hobby's (What do you like to do in your spare time?)
- Ask for a story (an you tell me a story?)
- Say that you ar fine or not good (I'm good/I'm not good)
And more!

# Why this project
I have done the minor Real Fake, Real Impact. During the minor, I immersed myself in AI and Digital Humans. One of the topics was learning the basics of python. With the knowledge learned, I created 4 different chatbots. Each chatbot was built with different techniques and with a diffrent purpose.

