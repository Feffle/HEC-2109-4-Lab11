# Lab Report 11 - Data Informatics Week 2

Isaac Stevens

April 4, 2024

## Summary of Lab 11
Lab 11 asks the user to create a code that will count the characters, words, and lines in a text file. Using Anaconda Assistant, information from Lab 10, and the lecture notebook I was able to modify the given code and expand it to complete the objective. Parts of the code were given from the lab files and by using it as a starting point, I began by asking Anaconda Assistant to create a code to count the characters, words, and lines in a file. The two files the lab wanted us to use to count were a poem by Robert D. Cowan and Barack Obama's Inaugural Speech. I downloaded both these files along with the lab files and properly linked them in the code when troubleshooting my code.

## Code Used in Lab 11
Part of the code was provided in the lab instructions and the rest was edited by me to complete the objective laid out by the lab instructions. Linked below is the final code I used to count the characters, words, and lines in Cowan's poem and Obama's speech.

[Link to Code](https://github.com/Feffle/HEC-2109-4-Lab11/blob/main/BAE%20305%20Lab%2011.ipynb)

## Conclusion
Lab 11 was overall far easier than Lab 10 was. The only modifications I had to make to the code were restricting the file to be read-only so counting could happen, setting up the counting function for characters, words, and lines through numbers or making use of the split function for spaces and periods, and linking both Cowan's poem and Obama's speech to be counted. I was able to accomplish this mostly by asking Anaconda Assistant for help and troubleshooting on how to complete the code. Carlos also asked the class to count sentences in both text files as well but I was unsuccessful in doing so due to the code reading periods at the end of sentences and periods in names such as Robert D. Cowan as both sentences. After some quick troubleshooting with Carlos, we realized an external grammar toolkit and more advanced code would be required to be able to properly count sentences in the program. After quick testing with Cowan's poem and Obama's speech, the final code correctly counts characters, words, and lines but not sentences. This lab taught me how to properly use the split function as well as simple objectives such as counting sentences sometimes require complex and external solutions depending on the task.
