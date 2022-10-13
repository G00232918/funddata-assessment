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
# Exercise - Adapt the code from the lecture notes to generate a 1000 character long string with weights based on the previous two characters.
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
