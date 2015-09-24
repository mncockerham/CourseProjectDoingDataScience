Contains R code for Shiny App as well as instructions document.

When the shiny as is opened or an in Rstudio it opens up a very simple Linear Regression Exploration Tool.

The contols on the right affect what you are looking at.

The First Box Choose a dataset allows for you to choose a R dataset to do the analysis with.

Currently it supports mtcars, airquality,swiss and rock.   Simply changeing this box allows for a different dataset to be loaded.

The 2nd box is Show Output:

It controls the number of rows displayed in the view tab to the right.

The 3rd box allows you to select a number for the response value in the linear model.  You will need to select the number of the column listed in the lower 
left hand corner of the first sheet.  

The 4th box allows you to select a number for the predictor value in the linear model.  You will need to select the number of the column listed in the lower 
left hand corner of the first sheet.  

The last bit of the screen is the listing of values for the response and predictor.

The report also has 4 tabs allowing you to understand the data set loaded.

Summary: Shows the basic values found in each column so you can see the range of calues allowed.

View: Shows the number of records selected in the Show Output tab

Cor:  Shows a simple plot showing how the data relates to eachother.

LM: Is the linear model.  Changing the respponse and predictor number changes the values looked at.