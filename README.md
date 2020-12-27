## Image-Convolution-Visualizer
A simple web application to visualize different convolutions by using image kernels, built with Python, Flask, HTML, and Bulma.

This application is a joint project between [Avery Ryoo](https://github.com/averyryoo) and [Jathushan Kaetheeswaran](https://github.com/jkaethee).

The project is intended to practice development with Python libraries such as NumPy, OpenCV, Scikit-image, and Python Imaging Library.
It also reinforces our web development skills with Python by allowing us to utilize Flask's framework for rapid development.

## Project Status
This project is currently in development. Future updates will include image uploads, extra convolutions, and more!

#### Example:   
![Image description](https://github.com/jkaethee/Image-Convolution-Visualizer/blob/master/image%20convolution%20examples.PNG)

## Installation and Setup Instructions

Clone this repository. You will need `python`, `virtualenv`, and `virtualenvwrapper-win` installed on your machine.

#### Set up a virtual environment:

`mkvirtualenv ImageConvolutionEnv`

#### Installation:

`pip install -r requirements.txt`

#### To Start Server:
**Please Note:** Currently, due to a caching issue, users must open DevTools in their browser and disable cache in order to see updated convoluted images! This issue will be fixed in future patches.

`flask run`  
