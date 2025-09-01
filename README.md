# Classification of Wine Types using the K-Nearest Neighbour Classifier
 This *project* helps us to **classify** the type of wine based upon the `features` such as **color intensity, presence of magnesium, phenols**,etc.

# Contents
1. [Dataset](#dataset)
2. [Exploratory Data Analysis](#exploratory-data-analysis)
3. [Scaling](#scaling)
4. [Evaluation](#evaluation)
5. [Libraries Used](#libraries-used)
6. [How to Run](#how-to-run)
7. [Acknowledgments](#acknowledgements)

## Dataset
 This project utilises the standard `load_wine` dataset to classify the target into **3 classes** - *class_0,class_1 and class_2* based upon it's features. This projects demonstrates the use of **K-Nearest Neighbour Classifier** to *classifiy* the *dataset*.We create a *dataframe* using `panda library` to create the **features matrix ( X )** and **target vector ( y )**.

## Exploratory Data Analysis
1. We have plotted a **histogram** of all the `wine features` which highlights about the *characteristics* of each feature!
2. Plotted a **boxplot** about the `alocohol content` of the respective *wine classes*.
3. There is also a `scatterplot` which depicts the **color intensity** of the alocohol.
4. Then, we dive into the **correlation matrix** of all the `features` in the *dataset*.
5. So, also we plotted a **scatterplot** of the __features__ including *alcohol*, *flavanoids*, *color_intensity*, *proline* and *wine class*.

## Scaling
 Then we used the **Standard Scaler** to scale down all the *features* in order to make our `dataset` look clean and easy to process and apply the model.
