### This is a repository for the Dog Breed Classifier made for the 2nd project of Udacity Deep Learning Program.

An example of using CNNs and Transfer Learning to classify the breed of a dog.

In this project, I'll walk through how to build a Convolutional Neural Networks (CNN) for image classification. 
In particular, the CNN developed for this project will attempt to predict the breed of a dog in a given photo. 
Just for fun, we'll also determine which dog breed a human most resembles when provided an image of a person.
The algorithm predicts 133 classes, which are the dog breeds. In the future I will add more classes and train the model in other animal breeds as well.
## Data

The training data for this project is located [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). This dataset contains 133 different breeds of dogs and is already split into train, test, and validation sets. 
Place the training, testing, and validation datasets in the `dogImages` folder.

### An output of the algoritm tested on a dog picture is the following:
<center><a href="https://imgbb.com/"><img src="https://i.ibb.co/LRQy0VC/Screenshot-from-2020-06-07-20-43-46.png" alt="Screenshot-from-2020-06-07-20-43-46" border="0"></a></center>

### And for a human:

<a href="https://imgbb.com/"><img src="https://i.ibb.co/94xHfT7/Screenshot-from-2020-06-07-21-23-04.png" alt="Screenshot-from-2020-06-07-21-23-04" border="0"></a>

#### I was concerned if the algorithm classifies as dogs other animals like a cat or a wolf for example. As it turned out the algorithm was able to recognize that this is not a dog but something that can not recognize.
A good example was a cat that looked like a dog that I found in google. At first sight a human could say that this is not a cat but a cute little dog. Luckily our alogrithm recognized it correctly.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/2n7Cmwc/Screenshot-from-2020-06-07-20-23-21.png" alt="Screenshot-from-2020-06-07-20-23-21" border="0"></a>

#### Another example that I was concerned was an animal that looks like a dog like a wolf for example. 
I tested the algorithm in a picture of a wolf as well:

<a href="https://imgbb.com/"><img src="https://i.ibb.co/Njjgq0s/Screenshot-from-2020-06-07-21-04-46.png" alt="Screenshot-from-2020-06-07-21-04-46" border="0"></a><br />
