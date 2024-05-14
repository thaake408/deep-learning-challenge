# deep-learning-challenge
# Module 21

# Overview of the analysis:
I've developed a sophisticated tool tailored for the nonprofit foundation Alphabet Soup. This tool utilizes cutting-edge machine learning techniques, specifically neural networks, to sift through applicant data and identify those with the highest potential for success if granted funding by Alphabet Soup. By analyzing various features within the dataset, I've engineered a binary classifier that accurately predicts the likelihood of an applicant's success. Our goal was to achieve a minimum accuracy of 75% with this model.

Results: Using bulleted lists and images to support your answers, address the following questions:

# Data Preprocessing

- **What variable(s) are the target(s) for your model?**

![Screenshot 2024-05-13 at 10 30 23 PM](https://github.com/thaake408/deep-learning-challenge/assets/150471324/79cf0fbf-ca1a-40db-8822-af871b02719b)


- **What variable(s) are the features for your model?**

![Screenshot 2024-05-13 at 10 29 46 PM](https://github.com/thaake408/deep-learning-challenge/assets/150471324/110809fd-5032-42fb-b8e2-af6172c04329)


- **What variable(s) should be removed from the input data because they are neither targets nor features?**

![Screenshot 2024-05-13 at 10 28 46 PM](https://github.com/thaake408/deep-learning-challenge/assets/150471324/ea1cd0fb-cdb1-44fe-bd0d-ef817df8b020)


# Compiling, Training, and Evaluating the Model

- **How many neurons, layers, and activation functions did you select for your neural network model, and why?**

![Screenshot 2024-05-13 at 10 32 15 PM](https://github.com/thaake408/deep-learning-challenge/assets/150471324/6b2258ef-3b89-48c8-97e9-5b91b01726b9)


- **Were you able to achieve the target model performance?**
  
![Screenshot 2024-05-13 at 11 35 50 PM](https://github.com/thaake408/deep-learning-challenge/assets/150471324/6747bbf1-a8a0-4099-8c1c-45ccbda6a3fd)

I was only able to reach a model performance of around 73%, 2% short of the target model performance.

- **What steps did you take in your attempts to increase model performance?**

![Screenshot 2024-05-13 at 10 34 57 PM](https://github.com/thaake408/deep-learning-challenge/assets/150471324/c5e02678-47c8-4de8-8289-b94b2365c7bb)

![Screenshot 2024-05-13 at 11 41 23 PM](https://github.com/thaake408/deep-learning-challenge/assets/150471324/73475954-5885-4c2d-98b6-ae02fdb9cfef)

![Screenshot 2024-05-13 at 11 39 17 PM](https://github.com/thaake408/deep-learning-challenge/assets/150471324/b5f1c829-3da3-4c51-bec6-958ed2fa4448)


I performed a Keras Tuner 3 times, changing up the number of epochs for each instance such as the examples pictured above. 
