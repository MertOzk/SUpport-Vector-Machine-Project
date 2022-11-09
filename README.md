# Support-Vector-Machine-Project

To be able to view this project you will need Python, Jupyter Notebook and Anaconda installed. You can click on the hyperlinks to look at a guide on how to install them. Please install the workbook and the dataset and change your directory to the downloaded folder to successfully run the workbook.

In this project I will be building a Support Vector Classifier Model to predict different classes of cancer ( 0 = Malignant, 1 = Benign) using the [Wisconsin Breast Cancer Dataset](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic) downloaded through sklearn. I will explore GridSearch to find the best parameters for the model and see how changing the parameters effect the outcome.

**Data Set Characteristics:**

    :Number of Instances: 569

    :Number of Attributes: 30 numeric, predictive attributes and the class

    :Attribute Information:
        - radius (mean of distances from center to points on the perimeter)
        - texture (standard deviation of gray-scale values)
        - perimeter
        - area
        - smoothness (local variation in radius lengths)
        - compactness (perimeter^2 / area - 1.0)
        - concavity (severity of concave portions of the contour)
        - concave points (number of concave portions of the contour)
        - symmetry 
        - fractal dimension ("coastline approximation" - 1)

        The mean, standard error, and "worst" or largest (mean of the three
        largest values) of these features were computed for each image,
        resulting in 30 features.  For instance, field 3 is Mean Radius, field
        13 is Radius SE, field 23 is Worst Radius.

        - class:
                - WDBC-Malignant
                - WDBC-Benign
