# funddata-assessment
* Practical notebooks
* Author - James Connolly
* Student_Number - G00232918
* Module -Fundamentals of Data Analysis

# 01-information-exercises

* Firstly urllib.request is imported to be able to handle internet HTTP requests. For this example Alice in Wonderland was used. With the book defined as an element, the text is in then decoded for the purpose of the program.
* The text is then set to all lower case so the code and can more usuable for the programmer. Anything that is not a letter or space is then removed. 
* To get random charcaters random is imported.
* The book is then set to a whole string to be weighted. To get an accurate repesentation of average, weight is used. More often, if you use just the average you can get biased results.
* Generate a string using the weights with the constraint of weights, this will lead to less suprises according Shannon.
* Once the string is generated, you then get how many times letters follow each other. This is known as model in relation to machine learning. 
* Set the element to get the "e" as twos, then the range is set. The next element is to get the previous character as the last character. Randomly pick the next character from the weights. The character is then appended to the twos element. 

# Exercise 1 - Adapt the code from the lecture notes to generate a 1000 character long string with weights based on the previous two characters.
* Set the parameters for the 2 characters.
* Set the range for a 1000 so the string would meet requirements.
* In the next elements they are to set where the character is pulled from in the dataset.
* Once the dictionaries are got, both dictionaries are put together/
* Set as an ordered list.
* Randomly pickk the next character after the set parameters.
* Then append the characters.

# Sources
* Lecture notes - https://github.com/ianmcloughlin/2223-S1-fund-data-analysis/blob/main/notebooks/01-information.ipynb
* https://towardsdatascience.com/3-ways-to-compute-a-weighted-average-in-python-4e066de7a719
* https://learn.microsoft.com/en-us/windows/ai/windows-ml/what-is-a-machine-learning-model - A model is to review certain patterns in set of data. It is a repeated decision or act that will show consistent results.
* https://stackoverflow.com/questions/45713887/add-values-from-two-dictionaries - Adding values for 2 dictionaries reference.

# Exercise 2 - Explain why the log of zero is undefined.
Explanatation is in the notebook.

* Sources
* http://mclph.umn.edu/mathrefresh/logs3.html#:~:text=2.-,log%200%20is%20undefined.,infinitely%20large%20and%20negative%20power. - Explaining logarithm.
* https://www.youtube.com/watch?v=j6scVL0Cp2k - Why is log of 0 undefined. Summarised in the notebook. 


# 02 - Randomness
* Exercise 1 - It is somewhat interesting that (5 * 4 * 3 * 2 * 1) perfectly divides (10 * 9 * 8 * 7 * 6) - there's no remainder.
If we only wanted exactly four heads as opposed to five, the equivalent calculation would be (10 * 9 * 8 * 7) / (4 * 3 * 2 * 1).
Does that evenly divide too? What is the formula in general?
Does it always come out as a positive whole number?

* Calculation to see does (10 * 9 * 8 * 7) / (4 * 3 * 2 * 1) divide evenlly and it returned a whole number -210/
* Binomial Distribution formula is then explained, which briefly is a formula that has two possible outcomes.
* An image to show Binomial Distribution with the elements explained.
* A brief summary of Binomial Distribution showing a negative number. It is when the probability is not set to 0.5.
* Coding example of negative Binomial Distribution.

* Sources
* https://corporatefinanceinstitute.com/resources/knowledge/other/binomial-distribution/ - Review of a definition of Binomial Distribution.
* https://numpy.org/doc/stable/reference/random/generated/numpy.random.negative_binomial.html - Negative Binomial explained with examples.

* Exercise 2 
* Explain why there are the same number of ways to get 4 tails as there is to get 4 heads.
* Brief explanation as to why you have the same chance of getting 4 heads or 4 tails.
* Coding example to demonstrate.

* Sources
* https://towardsdatascience.com/how-to-code-a-fair-coin-flip-in-python-d54312f33da9 - Fair coin toss explained with the an image.
* https://stackoverflow.com/questions/12540661/unibiased-flip-find-the-probability-of-how-many-times-heads-and-how-many-times#:~:text=Hey%20mate!%20%3A),can%20use%20the%20python's%20random%20. - Example of code for finding the probability of a fair coin toss. 

* Exercise 3
* Plot bar charts or histograms of any three different distributions listed at the following link:

https://numpy.org/doc/stable/reference/random/generator.html#distributions

* Dirichlet distribution
* This distribution is used in probability when you have more than 2 options.
* Firstly the variable and values need to be set.
* Tranpose the row elements int column elements.
* Then the sets are code.

* Sources
* https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.dirichlet.html
* https://www.healthline.com/health/how-many-hairs-on-a-human-head - Setting the range, 100000 was timing out so I had to set to a smaller range for the purpose of the exercise.
* https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.dirichlet.html


* Poisson distribution
* This distribution estimates how many times an occurs in a specified time. For example, how many times a person eats in the day.
* Get the random range.
* Use the Posssion method
* Plot the histogram.

* Sources
* https://www.w3schools.com/python/numpy/numpy_random_poisson.asp - Example of the Poisson Distribution with the elements explained.
* https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.poisson.html 

* Exponential Distribution
This distribution is a follow from Poisson, the difference being this is the probability distribution of the time between events in a Poisson point process.

* Sources
* https://www.alphacodingskills.com/numpy/numpy-exponential-distribution.php - Code example and explanation.