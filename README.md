# Prediction Assignment Writeup - Model Creation Steps.

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).

The assignment Data were made available online at the following links:

Data
The training data for this project are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

Overall, I estimated that it would take several steps to finish the project and draw the predictions.  Specifically, My process took five primare steps to complete and derive my predictison.

Initially, I was hoping to perform several classifier training; however, after reading about the available classification models, I selected the RandomForest model building approach because it provided a more robust approach to reach predictions with this type of data.  Furthermore the accuracy of the RandomForest was quite hight and I was very impressed with its results.  More over, the error rate that ws delivered with the RandomForest was under 1%, which ws quite impressive.
  
I explained my process within the body of my RMD file and also provided an HTML version, nevertheless, I thought it was necessary to also illustrate the steps on a separate page to render the process more robust and succint.

I followed the following five steps to reach my predictions:

    1. How ML model was constructed
    2. Cross validation usage description
    3. The expected out of sample error
    4. Model selection justification 
    5. Predict 20 different test cases from experimental model 
    
Please review my RMB and HTML pages to review my overall process.
