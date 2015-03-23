# LexAnalizer
Lexical Analyzer that recognizes the following elements:<br>
a. Identifiers<br>
  Its name can be formed with letters, digits and underscore, it must start with a letter or underscore, and the minimal size will be one character<br>
b. Reserved keywords<br>
  If, begin, end, do, wihle, print, read, then, real, string<br>
c. Int constants<br>
d. Double constants<br>
e. Special symbols<br>
  ',', ´;<br>
f. Assignement operator <br>
g. String´<br>

Ignores comments and indicates the lines of the source code where the lexical errors are.<br>

I thought it was a good idea to get the code to analize directly from a file, and then create another file with the symbols table and another one with the tokens list


