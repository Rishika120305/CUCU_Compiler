//Thoutam Rishika
//2022csb1138

TO RUN THE PROGRAM:

Open the terminal in the directory 2022CSB1138 and Enter the following commands to run the program :
        1. lex cucu.l
        2. yacc -d cucu.y
        3. gcc lex.yy.c y.tab.c
        4. ./a.out
        5.In the input.txt you can give Sample1.cu and Sample2.cu in order to get the respective results.
        6.It will generate lexer.txt and parser.txt for each input,txt we take.
        7.when Sample1.cu is given as input ,in the terminal it shows "Parsing Completed and No errors detected"
        8.when Sample2.cu is given as input ,in the terminal it shows "Errors Detected"

->>In the cucu.l file all variables anmes,kaywords,special characters and numbers.

->>In the cucu.y file it contains BNF grammer rules for the compiler.

->>Sample1.cu file contains the code which has correct synatx.

->>Sample2.cu file contains the code which has incorrect syntax.You can add your incorrect synatx code here and the program would parse it and print the error if it is wrong.In the terminal it will print Parsing Completed. 

->>lexer.txt file contains the output obtained by the cucu.l file, which are all the tokens in the code.

->>parser.txt file stores the output obtained by the cucu.y file, which is parsed by the cucu.y file and printed the steps and different types of statements in it.   
  -Displays Syntax errors.
  -Other errors as ERROR! followed by error message.
  -Parsing completed if syntatically correct code.
  -Errors Detected if syntax errors found. 
