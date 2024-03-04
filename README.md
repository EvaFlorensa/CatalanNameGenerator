# Catalan Name Generator
In this project, I aim to train a character-based language model to generate names of people in Catalan. In order to do so, two datasets will be used, both of them containing a list of names of people born in Catalonia, but at different periods of time. The first datased analysed is from the period 2010-2019, and the second one is from 1940-1949. Both of the datasets are collected from the website of the Institut d’Estadística de Catalunya, that belongs to the Generalitat de Catalunya. With these datasets, a language model is built up and then 20 names are generated for each period. The performance of the model is assessed by comparing the generated names with the real lists of names.

# Install
In order to run this code, you will need the following:
- Python 3.10.1
- pandas: for reading the two csv files containing the names and organizing them into two dataframes.
- torch and torch.nn.functional: for being able to work with the tensor and create the language model.
- matplotlib.pyplot and %matplotlib inline: for plotting figures.
- random: for generating random numbers, which is usefull for dividing the data and also for generating the names.

 # Author
 This project was created by Eva Florensa Villacampa.
