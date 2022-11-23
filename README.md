# Neural Networks Crash Course (kamarain/course_neural_networks)
This repo contains all materials for my neural networks crash course that is aimed for IT engineers who want to update their information about the cutting edge machine learning using neural networks. The course gradually develops from the fundamentals of linear regression and classification models to the state-of-the-art neural network architectures.

## Content
The current version of the course consists of the following four two hour lectures:

 1. Single neuron (1940's)
 2. Neural network (1980's) 
 3. Convolutional neural network (2010's)
 4. State-of-the-art neural network architectures (2020's)

Lectures are adapted for the needs and background knowledge of audience and the course is lectured in Finnish or English.

## Materials
The main "material" is me lecturing, but to help understanding these topics I provide supporting material such as:

 * Handwritten notes - see the notes/ directory
 * A Jupyter notebook of code examples - see the notebooks/ directory
 
 ## Python instructions
To run the provided code (Jupyter notebooks) you need to install Python. The best way is to use the Anaconda package manager. Install that by downloading the installer from the Anaconda Web site: [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution) .

After that, create environment and install the required packages. The following examples are for Linux, but to my experience work nearly unchanged also in MacOS: 
 
 ```
 $ conda create -n nnetcourse
 $ conda activate nnetcourse
 (nnetcourse) $ conda install python=3.9
 (nnetcourse) $ conda install jupyter
 (nnetcourse) $ conda install matplotlib
 (nnetcourse) $ conda install numpy
 (nnetcourse) $ conda install scipy
 ```

## Copyright and Licensing
 &copy; 2022 by Joni-Kristian Kamarainen licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
