# Boston House Pricing Prediction

## Software and Tools Requirementds

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line) 

Create a new environment:
    
    Ctrl+Shift+P -> search for Python:Create Environment in VSCode -> conda

<ul>
<li>Full Stack Web Application made using Krish Naik's youtube tutorial</li>
<li>Created a Regression model using Python 3.10.0 in Google Colab and Jupyter Notebook</li>
<li>Pickled the Regression model and the necessary Standarad Scaler</li>
<li>Linked with Github under the repository "bostonhousepricing"</li>
<li>Create a "requirement.txt" file which contains all the necessary libraries to be used</li>
<li>Create a Flask python file which contains the backend functions of the Web App</li>
<li>Create a HTML website which can be used to interact with the user </li>
<li>Link the flask file and the html in the forms attribute </li>
<li>Run the app.py file in the terminal and enjoy your Web App</li>
</ul> 

## <em> Boston Housing Dataset Details </em>
The boston dataset is uploaded from the sklearn library in the dataset attribute.
<br>
## Data Set Characteristics:  

    :Number of Instances: 506 

    :Number of Attributes: 13 numeric/categorical predictive. Median Value (attribute 14) is usually the target.

    :Attribute Information (in order):
        - CRIM     per capita crime rate by town
        - ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        - INDUS    proportion of non-retail business acres per town
        - CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        - NOX      nitric oxides concentration (parts per 10 million)
        - RM       average number of rooms per dwelling
        - AGE      proportion of owner-occupied units built prior to 1940
        - DIS      weighted distances to five Boston employment centres
        - RAD      index of accessibility to radial highways
        - TAX      full-value property-tax rate per $10,000
        - PTRATIO  pupil-teacher ratio by town
        - B        1000(Bk - 0.63)^2 where Bk is the proportion of black people by town
        - LSTAT    % lower status of the population