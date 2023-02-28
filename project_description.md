
## Project: Finding Donors for CharityML

## Project Overview
In this project, supervised learning techniques are applied and data insights are obtained from data collected for the U.S. Census to help CharityML (a fictitious charity organization) identify people most likely to donate to their cause. The following are the steps taken to achieve the proposed goal:
* The first Step is to  explore the data to learn how the census data is recorded. 
* applying a series of transformations and preprocessing techniques to manipulate the data into a workable format.
* evaluate several supervised learners of your choice on the data, and consider which is best suited for the solution. 
* optimize the model selected and present it as  solution to CharityML. 
* explore the chosen model and its predictions under the hood, to see just how well it's performing when considering the data it's given.




## Software Requirements

This project uses the following software and Python libraries:

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
.

## Starting the Project
This project contains three files:

- `finding_donors.ipynb`: This is the main file where the data preprocessing,transformations and predictions are made .
- `census.csv`: The project dataset.  load this data in the notebook.
- `visuals.py`: A Python file containing visualization code

# Project results 
The following results were obtained after series of trial and errors of various models and techniques on the provided data:
* The unpotimized model results and the model results after parameter tuning were :

|     Metric     | Unoptimized Model | Optimized Model |
| :------------: | :---------------: | :-------------: | 
| Accuracy Score |     0.857         | 0.8537          |
| F-score        |          0.7246   |   0.7241        |

* After  feature selection ,the following results were obtained:

|     Metric     | Unoptimized Model | Optimized Model |
| :------------: | :---------------: | :-------------: | 
| Accuracy Score |     0.857         | 0.8297          |
| F-score        |          0.7246   |   0.6666        |

More details and intentsive explanation of the executed process are provided in the finding_donors.ipynb file.
