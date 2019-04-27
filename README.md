# self-replicate
A self replicating program to print out its own source code. Based on an algorithm suggested by Ken Thompson.
http://delivery.acm.org/10.1145/360000/358210/reflections.pdf?ip=98.6.249.11&id=358210&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1556400202_519a719ab7ab1e98fded09efb1abd63d

A qucick rundown of the algortihm:
The char array (string) "s" is initialized as a global and contains the part of the source code starting right aftre the initialization, character by character (the values are ascii values). Main routine prints the import statments and the prints the initialization of char array "s'. after printing the initialization, it prints the whole char array (string) "s" as a string which is the code starting from main routine.
