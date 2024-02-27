With the help of Professor Matt Gitzendanner, these small projects helped me gain an understanding of neural networks, computer vision, and natural language processing, 
I trained deep learning models from scratch, learning tools, and tricks to achieve highly accurate results. I was also able to leverage freely available, 
state-of-the-art pre-trained models to save time and get the deep learning application up and running quickly.

The projects in this repository include:
  1.(intro 1-4) A model used to identify letters of the ASL alphabet (not including ‘J’ and ‘Z’ given that signing those letters requires motion). 
  Through the course of this project, I learned and utilized skills such as:
    A. How to prepare image data for training, creating a model, and then training the model with prepared data.
    B. How to address overfitting with the use of a convolutional neural network to increase the accuracy of the validation dataset.
    C. How to augment data with the purpose of giving the model a higher variance which in turn allows it to ignore unimportant features and select only the features 
    that are truly important in classification, allowing it to generalize better.
    
  2. (intro 5-6) A doggy door that only lets dogs (and not other animals) in and out. During this project, I learned:
    A. How to use Keras to load a very well-trained pre-trained mode, preprocess my own images to work with the pre-trained model, and use the pre-trained model to 
    perform accurate inference on the images
    B. How to Prepare a pre-trained model for transfer learning to perform transfer learning with a small dataset on a pre-trained model to further fine-tune the
    model for even better performance

  3. (intro 7) A headline generator that was able to generate generic news headlines using a relatively small subset of headlines from US national headlines. 
    With this project I learned:
    A. What sequence data and how it’s different from the stand-alone data used in the two earlier projects 
    B. How to prepare sequence data to use in a recurrent neural network to build and train a model to perform word prediction
    *** The headlines produced, although mostly grammatically correct do not provide much information for a potential given the limited size of the data set used***
     
  4. (intro 8) A model to recognize and distinguish between fresh and rotten fruits.
