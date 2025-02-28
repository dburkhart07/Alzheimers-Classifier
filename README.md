# Alzheimers-Classifier

An image-analysis and predictor for early Alzheimer's Disease based on MRI brain scanes.
This project makes use of creating a Convolutional Neural Network to train a model to make the most accurate predictions, validating and doing final testing along the way.
Model trained has consistent 94-95% accurcy, training on average for 8 minutes.

Attached in the repo is the ipynb file, as well as folders containing the data to properly train the model.

## Running

### Prerequisites
- Python 3.x

### Installing Libraries
To run this project, you will need the following libraries:  
- os
- matplotlib    
- tensorflow  
- numpy  

To install all of these at once, run the following command:

```bash
pip install os matplotlib tensorflow numpy
```
If this does not work, try making sure you have pip installed, updated to a compatible version, or using pip3 instead

### Testing code individually 
Use the Jupyter Notebook to run cells individually, allowing to see how each individual model performs at a time.<br>
IMPORTANT: Be sure to restart the Kernal before testing other models, to ensure that they are not being fit on previous models beforehand.

