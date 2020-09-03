20/02/2019
Josh Mullin 2067221
Thomas Hunt 4646221

To run our program in terminal navigate to file location and enter command
python3 look_whos_talking.py
The program will then wait for you to type a sentence to translate.

If you wish to input a file containing sentences to translate, make sure each sentence is on a new line and enter the command
python3 look_whos_talking.py <filename>.txt

If you wish to run the programs doctests then enter the command
python3 look_whos_talking.py -t -v


Our approach for solving this etude was to first sit down and brainstorm a way to tackle it.
We decided that the first step would be to determine the tense of the sentence by using the verb given.
We created a three dictionary to map verbs to their Māori translation; one dictonary each for past, present and future translation.
We created the three dictonaries so we would translate and determine the tense in one go.


We created doctests for several translation and for each of our helper methods to ensure
they work properly. We have included a text file in the zip file called test.txt with many
different sentences, subjects and tenses to translate.
We ran the doctests and compared the output directly with answers.txt
answers.txt is also in the zip file.