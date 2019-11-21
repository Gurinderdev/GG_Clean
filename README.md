# GG_Clean Semi-supervised Text matching

There are countless hours that are spent on string matching in general and name matching in particular. It is mind-blowing how many variations of a simple word ‘simple’ can be. Just a few to get the point across ‘Simplee’ , Smiple’…… You get the idea.

 
The goal of this project is to help in data cleaning using machine learning. The dream is to make it unsupervised, however, the challenges and unknowns are too many hence the goal is to make a supervised machine learning data cleaning library that would help many organizations and individuals save countless hours. 


Present scenario:

To the best of my knowledge, the present work in string match is based on some form of distance measure such as Euclidian or Levenshtein distance. These are good in my view when there is only one word to match with another, however, names and strings generally have more than one word and this causes an issue in using it.

 
What are we doing differently?

 
I believe that the source of the problem needs to be looked into. The issue comes from mistyping and hence a feature needs to be developed to take that element into account. For this I am developing a Key-board probability metric. This metric would help in calculating the likelihood that a letter has been mistyped. Apart from this, I am building on other features based on the words that we have. This will be updated on the main notebook.

