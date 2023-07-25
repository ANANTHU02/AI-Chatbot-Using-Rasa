# AI-Chatbot-Using-Rasa

An AI chatbot is an automated program that simulates a conversation with a human user through text or voice interactions. Chatbots use natural language processing (NLP) and machine learning algorithms to understand user input 
and provide relevant responses. Chatbots are commonly used in customer service, e-commerce, and other industries to answer common questions, provide assistance, and improve customer engagement. The development of
a chatbot involves several steps, including defining the use case, selecting the platform and technology, designing the conversation flow, training the machine
learning model, and testing and deploying. Chatbots can be integrated with various platforms, such as websites, messaging apps, and voice assistants. They can also be customized to reflect a brand's voice and personality, and
their performance can be monitored and improved through analytics and feedback.

RASA FRAMEWORK
Rasa is a flexible framework that allows developers to customize and extend its functionality to suit their
specific use case. Rasa can also handle large-scale conversational AI applications with ease. It can handle
multiple users and can be deployed on various platforms. Rasa provides ex-cellent NLP capabilities that allow
developers to understand user input and generate appropriate responses.
For the purpose of keeping all previous user-bot interactions, we need to connect the rasa server with the
database. Since Rasa allows database connectivity

RASA DIRECTORY
 actions.py: In Rasa, you can define custom actions that the chatbot can perform. These actions can
include making API calls, querying a database, or performing any other custom logic. Custom action
files are typically written in Python and saved with a ‘.py‘ extension.
nlu.yml‘: This file contains training data for Rasa NLU. It typically includes examples of user messages along with their corresponding intents and entities. This data is used to train the NLU model to
understand user inputs.

 rules.yml: The rules.yml file in Rasa is used to build rule-based policies for dealing with various user
inputs or discussion scenarios. Rules allow you to specify regular patterns or conditions that cause the
chatbot to do certain actions or responses. You can include the rules.yml file in your Rasa project as an
optional file to specify these rules.

stories.yml‘: This file contains example conversations or stories that map user inputs to corresponding
chatbot responses. Stories help train the dialogue management model in Rasa Core. Each story consists
of a sequence of user messages and the expected bot responses.

config.yml: This file specifies the configuration settings for training the NLU and Core models. It includes details such as pipeline configuration, featurization settings, policy configurations, and more. You
can customize this file to experiment with different training configurations.
credentials.yml: The credentials.yml file in Rasa is used to store and manage credentials for various
external services or APIs with which your chatbot may communicate. This file allows you to securely
store sensitive information needed for authentication and authorization, such as API keys, tokens, or
usernames/passwords

credentials.yml: The credentials.yml file in Rasa is used to store and manage credentials for various
external services or APIs with which your chatbot may communicate. This file allows you to securely
store sensitive information needed for authentication and authorization, such as API keys, tokens, or
usernames/passwords

• enpoints.yml: The endpoints.yml file in Rasa is used to specify the endpoints and connection details for
the many external services and platforms with which your chatbot communicates. It allows you to set
the NLU model, the Core model, and other external systems’ endpoints
