# count_words
This proyect count the number of occurrences, number of words and characters in the text.<br/>

The source code is the folder /src/main.java The program read a file .txt located in(src\data.txt).<br/>
If you want to change the text file location you can modify the folder path.<br/>

Change fileLocation in method readFileInString().<br/> 

String fileLocation = "src\data.txt";<br/>

#### Computacional complexity: <br/>
For to solve the problem, I focus initially to read correctly the data from text,<br/>
that should contain the words, spaces, and break rows.
To read the file use BufferReader, and after use, split to separate ever single word in a simple array.<br/>
After I move in this array with two for cycles, and analyze how many times is the word in the text, and find all the same words,<br/>
and save this word, and the number of repetitions in two arrays(words, and number of repetitions)<br/>
For calculate number of words, i only interest the numbers of values after to split, <br/>
and for calculate number of characters i need to remove \n values, because is not a value to add like a character<br/> and after only show the lenght of this String.


#### The output of program is like:<br/>

lumu lumu lumu lumu lumu illuminates illuminates attacks and adversaries<br/>
lumu illuminates all attacks and adversaries<br/>

16 words<br/>
116 characters<br/>

lumu: 6<br/>
illuminates: 3<br/>
attacks: 2<br/>
and: 2<br/>
adversaries: 2<br/>
all: 1<br/>
