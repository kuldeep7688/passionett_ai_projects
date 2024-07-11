# Post Recommendation Model

Model for recommending posts to users.

## Initial Approach 1

- Recommend posts from users with the same industry interests.

## Initial Approach 2

- Bag of Words model to get probablity of each post having the three classes
  - Data will be created using Chat GPT and information from Onet data
- Will be a multi-label model. A post can be of multiple categories
- Will be deployed in the AWS and directly runs on an any post submitted to the platform
- Dockerized deployment; will need to just directly plug in the api
- Posts will be recommended to a user using the probability score from the model.
- https://www.onetonline.org/find/descriptor/browse/2.C/2.C.1/2.C.3/2.C.4

## Future Improvements

- The initial approaches will help us to create some training data using the User feedback
- More advanced but simpler models (which can be deployed easily) like SVM. And more features from the user and posts.
