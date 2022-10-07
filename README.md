# funddata-assessment
* Practical notebooks
* Author - James Connolly
* Student_Number - G00232918
* Module -Fundamentals of Data Analysis

# 01-information-exercises
# Adapt the code from the lecture notes to generatea 1000 character long string with weights based on the previous two characters.
* Firstly urllib.request is imported to be able to handle internet HTTP requests. For this example Alice in Wonderland was used. With the book defined as an element, the text is in then decoded for the purpose of the program.
* The text is then set to all lower case so the code and can more usuable for the programmer. Anything that is not a letter or space is then removed. 
* To get random charcaters random is imported.
* The book is then set to a whole string to be weighted. To get an accurate repesentation of average, weight is used. More often, if you use just the average you can get biased results.
* Generate a string using the weights with the constraint of weights, this will lead to less suprises according Shannon.
* Once the string is generated, you then get how many times letters follow each other. This is known as model in relation to machine learning. 
* Set the element to get the "e" as twos, then the range is set. The next element is to get the previous character as the last character. Randomly pick the next character from the weights. The character is then appended to the twos element. 

# Sources
* Lecture notes - https://github.com/ianmcloughlin/2223-S1-fund-data-analysis/blob/main/notebooks/01-information.ipynb
* https://towardsdatascience.com/3-ways-to-compute-a-weighted-average-in-python-4e066de7a719
* https://learn.microsoft.com/en-us/windows/ai/windows-ml/what-is-a-machine-learning-model - A model is to review certain patterns in set of data. It is a repeated decision or act that will show consistent results.


