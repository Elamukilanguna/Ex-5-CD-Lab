
RECOGNITION OF THE GRAMMAR(anb where n>=10) USING YACC
# Date:9.5.25
# Aim:
To write a YACC program to recognize the grammar anb where n>=10.
# ALGORITHM
1.	Start the program.
2.	Write a program in the vi editor and save it with .l extension.
3.	In the lex program, write the translation rules for the variables a and b.
4.	Write a program in the vi editor and save it with .y extension.
5.	Compile the lex program with lex compiler to produce output file as lex.yy.c. eg $ lex filename.l
6.	Compile the yacc program with yacc compiler to produce output file as y.tab.c. eg $ yacc –d arith_id.y
7.	Compile these with the C compiler as gcc lex.yy.c y.tab.c
8.	Enter a string as input and it is identified as valid or invalid.
# PROGRAM:
C: \Users \admin>cd C: \Dev-Cpp\TDM-GCC-64\bin
C: \Dev-Cpp\TDM-GCC-64\bin>flex expr5.1
C: \Dev-Cpp\ TDM-GCC-64\bin>bison -dy expr5. y
C: \Dev-Cpp\TDM-GCC-64\bin>gcc y. tab.c lex. yy.c -w

# OUTPUT
![Screenshot (247)](https://github.com/user-attachments/assets/324d4962-7f7f-42aa-85ef-4cf08bb6da82)

# RESULT
The YACC program to recognize the grammar anb where n>=10 is executed successfully and the output is verified.
