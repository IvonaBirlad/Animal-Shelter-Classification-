# Animal-Shelter-Classification-

## Data
The dataset is part of a Kaggle competition named Shelter Animal Outcomes. It is made up of two CSV files, one containing the test set and the other, the training set. The dataset contains 10 text features: AnimalID, Name, DateTime, OutcomeType, OutcomeSubtype    AnimalType, SexuponOutcome, AgeuponOutcome, Breed, Color and 38187 dimensions (26730 for the training set and 11457 for the test). 

The dataset can be downloaded here: https://www.kaggle.com/c/shelter-animal-outcomes/data?select=test.csv.gz 

## Problem 
I aim to build and train a classification algorithm capable of predicting the dependent nominal variable OutcomeType, which represents the fate of an animal in the shelter: successful adoption, transfer to a different institution, return to the owner or euthanasia. The relevant features consist of nominal data (breed, color, sex, species) as Ill as ordinal data (age, date of outcome).

Such an algorithm may facilitate the shelter’s logistics and ultimately improve the welfare of the animals themselves, since knowing the most likely outcome can help the staff plan around their capacity and perhaps focus their efforts on saving those animals most in danger of suffering one of the unfortunate outcomes.
