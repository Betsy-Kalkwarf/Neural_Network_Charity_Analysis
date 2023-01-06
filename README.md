# Neural_Network_Charity_Analysis

## Overview

AlphabetSoup, a philanthropic organization, raises and donates money to create a better world. Unfortunately, not all of the companies that receive donations from AlphabetSoup use the funds appropriately. Therefore, a model is being created to help determine which organizations are worth receiving donations from AlphabetSoup and which companies should be avoided.

## Results

### DataProcessing:
- Target variable: “IS_SUCCESSFUL” whether the donation was a successful investment or not
- Feature variables: “APPLICATION_TYPE”, “AFFILIATION”, “CLASSIFICATION”, “USE_CASE”, “ORGANIZATION”, “STATUS”, “INCOME_AMT”, “SPECIAL_CONSIDERATIONS”, “ASK_AMT”
- Removed variables: “EIN”, “NAME”

### Compiling,Training, and Evaluating the Model
- I tried multiple different combinations of neurons, layers, and activation functions. None of the combinations I tried got the model to 75%+ accuracy.
- I was unable to achieve the target model performance.
- I tried many different changes to improve the model’s performance. Each change is shown in comments. I first changed the classification for “other” in application type to less than 700, instead of 500. I tried adding a third layer and then deleting the third layer. I tried adjusting the number of hidden nodes. I also switched between Relu and Sigmoid for the different layers.

##Summary
Overall, this model would have received a passing grade in high school but I wouldn't recommend AlphabetSoup use it. They should focus on companies they are more sure will utilize the donations well. I would continue to play around with the different aspects of the neural network to see if the accuracy could be increased. I may even try using less target variables, especially if certain variables may have a larger impact on the successful use of donations.
