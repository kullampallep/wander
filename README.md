# Wander

## Summary
- Developed Wander, a machine learning–based travel app that recommends city attractions based on users past interests during 48 hour hackathon.
- Curated a custom dataset of tourist spots using Generative AI and trained models in Google Colab with scikit-learn and TensorFlow.
- Built a dynamic web app using Anvil to collect user feedback and refine recommendations in real time.

Note: Since our application depends heavily on user-generated data, we used Generative AI to curate a list of tourist attractions in various cities including features such as rating, cost, address, suitability, and estimated time. Once of our team members, acted as a user of our app, deciding whether or not they would visit these stops. Based off of this, we were able to train multiple machine learning models (Logistic Regression, Decision Trees, Random Forest, Neural Networks, and CNN) and found that CNN resulted in 82 percent. However, we had trouble integrating CNN with our prediction dataset and used our Logistic Regression Model which had a high accuracy as well. We then used this to predict tourist attractions in Charlottesville the user would find interesting with our model and displayed in our Anvil App which integrated Google Collab where we wrote the Machine Learning code with scikit-learn and TensorFlow.

## Links:
Devpost Link: https://devpost.com/software/wander-vjhdyn
Google Colab Link: https://colab.research.google.com/drive/1jXftxf3GnJ5gGy6L0xja7xTXr8mawW_Z?usp=sharing
Anvil: https://twin-noisy-degree.anvil.app/
