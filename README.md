
## Table of Contents (Optional)

- [Data collection](#Data collection)
- [Understanding the data](#Understanding_data)
- [Data Cleaning](#Data_Cleaning)
- [Model Architecture](#Model_Architecture)

---


## Installation
### from conda
- `conda install -c anaconda tensorflow-gpu` 
### from pip
- `pip install tensorflow-gpu` 

## Data collection
- we are using inbuit data provided by library
---

## Understanding_data
- data sets consist of 70000 handwritten 28x28 grey pixel images.
- we are just using 60000 images only for this

## Data_Cleaning
- data sets is mostle preprocessed we just have to  rescale the image from -1 to 1
w function we can see our batch images

### Model Architecture
##  Generator
- The goal is to get the generator to create fake images that are convincing enough to trick the discriminator into thinking that they're real. 
- the generator has to craft a coloured photo that's realistic-looking enough for the discriminator to believe it's a genuine photo like the ones it's seen in the training data

##  discriminator 
- the generator is terrible and the discriminator can easily tell it has done a bad job.
- Over time, however, with more training, the generator manages to fool the discriminator. 

## now after writing the both the method its time for training and generates some image and check the loss of both the model and see how well they perform