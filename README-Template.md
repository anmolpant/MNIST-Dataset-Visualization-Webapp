# MNIST-Dataset-Visualization-Webapp

The MNIST handwritten digit classification problem is a standard dataset used in computer vision and deep learning.

Although the dataset is effectively solved, it can be used as the basis for learning and practicing how to develop, evaluate, and use convolutional deep learning neural networks for image classification from scratch. This includes how to develop a robust test harness for estimating the performance of the model, how to explore improvements to the model, and how to save the model and later load it to make predictions on new data.

In this project, you will discover how to develop a convolutional neural network for handwritten digit classification from scratch and display the output in the form of an interactive web application using python's streamlit framework.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development purposes.

### Prerequisites

On my local machine, I've used: 
python 3.8, 
tensorflow 2.2, 
streamlit 0.61.0, 
and flask 1.1.2 
as well as python 3.6.8, tf 2.1, streamlit 0.60 and flask 1.1.2


### Installing

Install the above dependencies via pip. And run the ML flask server from the command prompt before executing the streamlit application.

Run the ML flask server from the appropriate directory.

```
$directoryName/Path/ python3 ml_server.py
```

Execute the streamlit application

```
$directoryName/Path/ streamlit run app.py
```

This will get the frontend of the application containing the ML model running.

## Testing the application on a random input

Press the "Get random prediction" button to test the app against a random entry in the dataset. 

### Break down and analysis

The application visualizes the outputs of each layer for a given input and predicts the handwritten digit to a certain degree of confidence which is highlighted in the final layer. The lightness in colour denotes a higher degree of confidence in prediction and thereby ensures better accuracy. 


### Sample working and output 

![alt text](http://url/to/img.png)


## Built With

* [Streamlit](https://docs.streamlit.io/en/stable/) - The web framework used.
* [Keras](https://keras.io/) - Used to code and train the neural network. 
* [Flask](https://flask.palletsprojects.com/en/1.1.x/) - Creation of model server.

## Contributing

Please feel free to fork the above repository and open an issue first before sending a pull request.
 

## Authors

**Anmol Pant** - *Initial work* - (https://github.com/anmolpant)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Shoutout to the deeplearning.ai specialization on coursera for their easy to grasp and hands on courses.

