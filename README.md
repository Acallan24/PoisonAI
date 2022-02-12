# PoisonAI
AI for detecting poisonous and non-poisonous flowers. 

************************************************************
Project Presentation

Identifying the problem
- Millions of people interact with nature on a day-to-day basis. 
- Plants are an integral part of nature. But many people don’t know which plants to interact with as there are a lot of poisonous plants. 
- Numerous individuals get hurt, injured etc. while hiking or visiting forests because of these poisonous plants. 

SOLVING THE PROBLEM
- While there may be traditional ways of solving such problems. Things like a picture book or describing the plant. There is a lot of limitation to such approach. 
- The limitation is that a plant may look alike to another plant which is not toxic. But, in its description, may be the same. This causes confusion and faces a treat to the approach mentioned. 

Computer VSION 
- This is where the use of AI is so necessary. AI does not only analyze the shape but the texture as well as other characteristics  too. 
- Thus, it fills in the gap of the approach mentioned in the previous slide. 

Proposal
- My aim is to use a web scraper and AI to train a model which is bale to recognize the poisonous and nonpoisonous plants.
- The idea is that the users should be able to simple upload an image of a plat that they see in the forest and be able to confirm if that plant is dangerous or not. 

TECHNOLOGIES
- TensorFlow
  - Helps develop and train a CNN
  - Thus, not all code will be written from scratch. 
- Matplotlib 
  - Visualize data
- CV2
  - Resize images
- NumPy 
  - Arrays calculations
  - Azure AI 
  - For searching Bing images of the plants and making a data set. 

Final Apporach
- Using the technologies mentioned in the previous slide, I will be creating a conventional neural network for two plants. 
- One will be poisonous and the other, normal. For getting the images, I will use bing’s extension in the Azure AI portal from Microsoft. 
- TensorFlow will be used along with CV2 to manipulate images and create a model which can be used by simply uploading an image.
- While I do not have the resources to do all plants on earth. This model will be enough to prove the concept. This is its one limitation. It only forks for the two plants trained. 

Reference - https://data-flair.training/blogs/cats-dogs-classification-deep-learning-project-beginners/
