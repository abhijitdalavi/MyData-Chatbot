# MyData-Chatbot
Chatbot connected to APIs to read passport, and forms data from images, then store it in a private database for each user.

# How to use this experience:
You will need AWS developer account, Facebook page, Facebook Developer account, and node.js. First, get the page access token for the Facebook Messenger ChatBot, then setup the AWS access token and secret. Next, subscribe to the Mphasis Autocode WireframeToCode model in Amazon Sagemaker, then create an end-point and set it up in the readPassport.js. Now, create a new environment in Amazon Elastic Beanstalk, zip the project, then deploy the project. Finally, add the PAGE_ACESS_TOKEN in the environment variables.
