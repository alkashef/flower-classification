# Flower Classification

In this project, I train an image classifier to recognize different species of flowers. That is, given an image of a flower, it returns its species. I'm using [this dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html) of 102 flower categories. A few examples can be seen below. 

<img src='https://github.com/alkashef/flower-classification/blob/master/assets/Flowers.png?raw=1' width=500px>

## Project Setup

`main.ipynb` contains the project code and documentation. The notebook is designed to run in any of the following setups by setting a value of a single variable (`colab`):

1. Fork and clone the repo to a machine which has `Anaconda` and `PyTorch` and run it. 
   - Set `colab = False`
2. Open it from [Google Colabs](https://colab.research.google.com) and run it there.
   - On Colabs: *File > Open notebook... > GITHUB*
   - In the notebook: `colab = True`
   - The notebook can be modified in Colabs editor and checked-into Github automatically: *File > Save a copy to Github...*

