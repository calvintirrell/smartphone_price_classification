# Smartphone Price Classification

Utilizing classification algorithms to solve the business problem for how a new smartphone company should price their phone.
Taking into account various aspects of hardware specifications such as screen size, storage space, battery size, etc - these will all be used to help determine the final estimated sale price of the new phone model.

[This project idea is from this Kaggle competition.](https://www.kaggle.com/iabhishekofficial/mobile-price-classification)

To view the actual Jupyter Lab that I have been working in - go to the 'Jupyter Notebooks' folder and select the file: 'smartphone_pricing.ipynb'.

The conclusion I came up with is that the best model to use for this problem is the KNearestNeighbors model.
It had similar accuracy performance to the linear regression model and better F1 Score compared to the GradientBoosting Classifier model.
F1 Score is important as it is a balance (tehcnical term: harmonic mean) of the Precision and Recall scores.

The final result is that this new smartphone that is being released should be priced in the lowest pricing bracket.
However, the data (of various mobile phones) does include a lot of older phones (that are now cheaper in pricing).
I believe this may be influencing the result that a brand new smartphone should be priced at the lowest range.
This doesn't mean that the new phone shouldn't be at that price point since it might not have the hardware of the higher priced phones.

Each section will have a title or information in non-technical terms to provide context for the code below it.

Thanks for taking a look!
