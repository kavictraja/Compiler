# Compiler
STEPS TO COMPILE:

1.compile the lex file: flex filename.l
2.compile the yacc file: yacc -d filename.y
3.compile c++ programs: g++ lex.yy.c filename.tab.c -lfl
4.execute the file: ./a.out<inp.txt

CONCEPTS INCLUDED

1.convert unmatched if to matched if.
2.convert for loops and do while loops into while loops.
3.construction of syntax tree.
4.three address generation & backpatching.
5.control flow graph.
6.Directed Acyclic Graph(DAG) for basic blocks.
7.copy propagation & constant folding.
