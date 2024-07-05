# CUCU_Compiler
<p align="center">
  <h1 align="center">Cucu Compiler </h1>
this is a cucu language compiler.


# Commands to generate compiler 
```
bison -d cucu.y
flex cucu.l
g++ cucu.tab.c lex.yy.c -ll -o cucu
```

# Commands to compile Sample1.cu
```
./cucu Sample1.cu
```
<p align="center">
  <h2 align="left">Language defination </h2>
  <p>you can find it in Language .txt</p>

<p align="center">
  <h2 align="left">Output Files </h2>
  <ul>
  <li>Lexer.txt
  <li>Parser.txt
  </ul>
  <h3 align="left">Lexer.txt </h2>
 It contains tokens parsed and following errors:

#  
```
