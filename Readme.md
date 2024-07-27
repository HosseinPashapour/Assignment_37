# Assigment 37


## Use Lobe to Train Data
input data are 3 type different type of Animals

## Input

<img src="Output\Screenshot 2024-07-26 071949.png" width="400">

## Results

<img src="Output\Screenshot 2024-07-26 072200.png" width="450">

<img src="Output\Screenshot 2024-07-26 072540.png" width="450">


-----------------------------------------


## Machine Learning
In the machine learning section, I practiced:
- **1- Mean, Median, Mode:** Calculating and understanding these basic statistical measures to summarize data.
- **2- Standard Deviation:** Measuring the amount of variation or dispersion in a dataset.
- **3- Percentile:** Understanding the value below which a given percentage of observations in a dataset falls.
- **4- Data Distribution:** Visualizing and analyzing how data is spread across different values.
- **5- Normal Data Distribution:** Studying the properties of normally distributed data, which follows a bell curve.
- **6- Scatter Plot:** Creating scatter plots to identify relationships between two variables.
- **7- Linear Regression:** Implementing linear regression to model the relationship between a dependent variable and one independent variable.
- **8- Polynomial Regression:** Extending linear regression to model relationships using polynomial terms.
- **9- Multiple Regression:** Modeling the relationship between a dependent variable and multiple independent variables.
- **10- Scale:** Normalizing or standardizing data to bring all variables to a common scale.

## How to Install
Run following commend :
```
pip install -r requirments.txt
```
## How to Run
Execute this command in terminal :
```
jupyter nbconvert --to script Machine_Learning.ipynb
```

## Sample Results
Confusion Matrix  
<img src="Output\Confusion Matrix.png" width="450">

Decision tree   
<img src="Output\Decision tree.png" width="450">


-----------------------------------------

## Matplotlib
In the matplotlib section, I engaged in exercises that covered:

- Basic plotting functions
- Customizing plots with titles, labels, and legends
- Creating various types of plots such as line plots, bar charts, and histograms
- Adjusting plot aesthetics and styles

## How to Install
Run following commend :
```
pip install -r requirments.txt
```
## How to Run
Execute this command in terminal :
```
jupyter nbconvert --to script Matplotlib.ipynb
```

## Sample Results
Combine Color Size and Alpha  
<img src="Output\Combine Color Size and Alpha.png" width="450">

Matplotlib Pie Charts  
<img src="Output\Matplotlib Pie Charts.png" width="450">


-----------------------------------------

# Data_Set_Numbers
The Python code in this section processes an image containing various representations of numbers from 0 to 9. The code reads the image, crops it into separate sections for each number, and saves the cropped sections into specific folders.
### Explanation
- **Reading the Image:** The image is read in grayscale mode using OpenCV.
- **Displaying the Image:** The image is displayed using matplotlib to visualize the input.
- **Cropping the Image:** The image is divided into ten sections, each representing a different number from 0 to 9.
- **Creating Output Directories:** For each number, a directory is created if it doesn't already exist.
- **Saving Cropped Images:** Each section is further subdivided, and the resulting smaller images are saved into their respective directories.
- This code helps in organizing and preparing a dataset of images representing different numbers, which can be useful for machine learning tasks such as digit recognition.
what they've learned through interactive exercises.


## How to Install
Run following commend :
```
pip install -r requirments.txt
```
## How to Run
Execute this command in terminal :
```
python Split_Numbers.py
```

## Input

<img src="Input\mnist.webp" width="1000">


## Sample Results

<img src="Output\Split_Number\9\1.jpg" width="350">
<img src="Output\Split_Number\3\12.jpg" width="350">

-----------------------------------------







