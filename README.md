# AWS-deepracer
Notes and exercises for the AWS Deep Racer Student League

### A training model algorithm: 
- iteratively update model parameters to minimize some loss function. By model paramaters, we mean the configuration that changes how the model behaves.
- A loss function is how close the model is to its goal
- We must split our data so that one is for training our model and the other is for testing to evaluate the model
- The training process:
1. Feed the training data into the model
2. Compute the loss function on the results
3. Update the model parameters to reduce the loss.
- HyperParameters: settings on the model that are  not changed during training. This can affect how quickly/reliably the model trains like the number of clusters the model should identify

### Types of models:
<img width="941" alt="Screen Shot 2023-07-09 at 4 02 03 PM" src="https://github.com/26samaahmed/AWS-deepracer/assets/111910374/456b9234-4b2a-40f2-9834-efd5cf78f3b2">
<img width="951" alt="Screen Shot 2023-07-09 at 4 02 23 PM" src="https://github.com/26samaahmed/AWS-deepracer/assets/111910374/3970783f-455e-4f2b-bce0-dfdda07debc7">

### Regresions: 
A task in supervise ML that is used to understand the relationship between multiple variables from a dataset
### Continuous:
Floating point values that have an infinite range of possible values. The opposite of continues is categorical or discerete value which take a limited number of possible values
### HyperPlane: 
Used to seperate data into different categories based on their characteristics

### Vectorization:
Changing non numeric data into numeric data

### Bag of Words:
A technique that counts how many times a word appears in a document then transforms that information into a dataset

### Silhouette Coefficients:
A score from -1 to 1 describing the clusters found during modeling. A score near zero indicates overlapping clusters, and scores less than zero indicate data points assigned to incorrect clusters. A score approaching 1 indicates successful identification of discrete non-overlapping clusters.

### Stop Words:
Word removed by NLP tools like "the" and "a"

### Neural Networks:
A collection of simple models that are connected together. This models are called neurons. The connection between neurons is called weights
