# Conversational AI and Natural Language Processing (NLP) Tutorial
Natural Language Processing (NLP) and Conversational AI has been transforming various industries such as Search, Social Media, Automation, Contact Center, Assistants, and eCommerce. It has undergone several phases of research and development. Prior to the 1990s, most systems were purely based on rules. Then came machine learning based systems, however, it was still hard to manage multiple domains and scenarios. Post 2013, Transfer learning and Deep Learning based systems further enhanced the performance substantially by scaling the system to millions of users across a variety of applications. More recently, Transformers based models have taken the AI research and product community by storm through a variety of benefits. 

Despite significant progress in the past decade, most systems rely on large amounts of data annotation or require experts in the loop. With recent no code or low code tools, it is possible for developers with minimal coding or NLP/Conversational AI background to be able to build applications. 

In this talk/tutorial/crash course, I will be starting with some background in Deep learning, NLP and Conversational AI and then gradually move towards advanced topics such as Transformers based Large Scale Language Models such as BERT and building complex Conversational Bots. I will walk the audience through hands-on examples and how they can leverage such techniques in their applications.



## Installation and Pre-requisite
- git clone git@github.com:chagri/Conversational-AI-NLP-Tutorial.git
- cd Conversational-AI-NLP-Tutorial
- pip install --ignore-installed -r requirements.txt

If you can get OpenAI GPT-3, great! This is optional.
https://beta.openai.com/



## Examples

1. NLP:
    a. Text Classification: https://github.com/chagri/Conversational-AI-NLP-Tutorial/blob/master/nlp/text-classification.ipynb
    b. Tagging and Named Entity Recognition: https://github.com/chagri/Conversational-AI-NLP-Tutorial/blob/master/nlp/tagging-nert.ipynb
    c. Translation: https://github.com/chagri/Conversational-AI-NLP-Tutorial/blob/master/nlp/translation.ipynb
    d. Summarization: https://github.com/chagri/Conversational-AI-NLP-Tutorial/blob/master/nlp/translation.ipynb


2. Conversational AI:
    a. Question Answering:
    b. Reminder Bot: https://github.com/chagri/Conversational-AI-NLP-Tutorial/tree/master/conversational_ai/rasa_examples/reminderbot  
    c. Task based virtual assistant: https://github.com/chagri/Conversational-AI-NLP-Tutorial/tree/master/conversational_ai/rasa_examples/e2ebot
    d. Commands:
        - Train NLU only: "rasa train nlu"
        - Train NLU and Dialog Management: "rasa train"
        - "rasa interactive"	Starts an interactive learning session to create new training data by chatting to your assistant.
        - "rasa shell"	Loads your trained model and lets you talk to your assistant on the command line.
