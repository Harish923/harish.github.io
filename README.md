# Getting Started
### Webpage
You can train,test Convolutional Neural Network [here](https://harivardhanr.github.io/digitsclassifier).
The webpage contains the following buttons __guess__,__train__,__test__ and __clear__.
### Guess button
The model outputs the digit you drew on the canvas.It also outputs the probability of other numbers it thinks the digit is,darker the digit's 
corresponding cirle higher the probability.
### Clear button
clears the canvas.
### Test button
used to test how well the Neural network has been trained.By default the testing images are 1000 you can test the Neural network with 
more than 1000(upto 10,000) images by changing the value of totalTestData in sketch.js.
### Train button
used to train the model.You can also change the default value of totalTrainData upto 60,000 to train the model with 60k images.
More the trainImages the better the model's outputs.
###### NOTE : training with more number of images in low-end PC may take a long time.
# Built with
 * [p5.js](https://p5js.org/). p5.js a JS client-side library for creating graphic and interactive experiences, based on the core principles of Processing.
 * [tensorflow.js](https://www.tensorflow.org/js). TensorFlow.js is a JavaScript Library for training and deploying machine learning models in the browser.
 
