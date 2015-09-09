You are reading the README.md file in the calculate GitHub repository for Russ Robbins. This is a project that is a work in progress. 

The purpose of the code in this repository is to provide some insight into how I am using or can use Python. The package is far from complete. When/if completed this will be the backend for an interactive binary classification confusion matrix that will allow you to enter three of any of the joint and conditional probabilities and in return receive all the other probability values back. In addition, ratios and derivative ratios such as positive likelihood and diagnostic odds will be provided. The current design relies on 40 probability equation-based functions, a dictionary that stores probabilities, a dictionary that dispatches functions, and an argument parser which captures and passes command line arguments.

Concurrently, I am building an AngularJS-based front end. In its basic grid-based form, it will accept the three inputs and present the results of this backend. In a more advanced form, it could show the user the path from the three inputs to the probabilities and their ratios.

Besides providing a glimpse into my ability to design and develop simple applications, the result will provide individuals that are learning probability a method to see the relationships of probabilities, their complements, their intersections, their conditionalities, as well as how all of these relate to Bayes' Rule.
