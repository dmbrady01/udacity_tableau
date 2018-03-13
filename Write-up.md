# Creating a Tableau Story with Titanic Survival Data 

My [initial](https://public.tableau.com/profile/daniel2654#!/vizhome/TitanicFailure/TitanicFailure) tableau story

My [final](https://public.tableau.com/profile/daniel2654#!/vizhome/TitanicFailureFinal/TitanicFailure) tableau story


## Summary
The Titanic dataset contains demographic information from a subset of the passengers onboard
the Titanic. I have created a tableau story exploring what features were predictive 
of survival.

## Design
* There was some initial preprocessing (detailed in the jupyter notebook) to only include some of the factors and to fill in missing data.
* Survival rate (number of survivors/total number of people) was the measure across nearly all visualizations.
* Since all the visualizations were comparing percentages, bar charts made the most sense. A quick comparison of bar height is all that is needed to 
get a sense of the data.
* The only exception to above was with the parent/sibling matrix. I thought that would be interesting to include all combinations (removed later due to confusion).
* All factors were group data (I binned ages), so it made sense to have factors on the x-axis and survival rate on the y-axis.
* I grouped certain features into a dashboard to break up the monotonic nature of most stories (one chart per slide).
I thought it would be a bit fun to organize them in ways that lended to cheeky titles - A/S/L, Grey Poupon, and Loneliness is a Warm Gun

## Feedback
Feedback: Person #1
* Should begin with a summary slide instead of going straight to survival percentages. 
    * Added a dashboard with basic survival information about the Titanic 
* The colors can be a bit harsh. 
    * Softened the color palette

Feedback: Person #2
* I do not know what embarkation city means. 
    * Changed embarkation to departure
* Remove the with/without for chart titles that have them. 
    * Removed with/without from titles of parent and sibling/spouse charts
* The parents/siblings survival matrix is confusing. 
    * I removed it

## Resources
[Titanic Dataset](https://www.kaggle.com/c/titanic)

[Titanic (1997 film) Wikipedia Page](https://en.wikipedia.org/wiki/Titanic_(1997_film))

## Data
[Finalized Dataset](https://raw.githubusercontent.com/dmbrady01/udacity_tableau/master/Final_titanic_dataset.csv)