###############################################################
# Program:
#     Checkpoint 13b, Rule of Three
#     Brother Comeau, CS165
# Author:
#     Yiqi Wang
# Summary:
#     Summaries are not necessary for checkpoint assignments.
###############################################################


a.out : numberList.o check13b.o
	g++ numberList.o check13b.o

numberList.o : numberList.h numberList.cpp
	g++ -c numberList.cpp

check13b.o : numberList.h check13b.cpp
	g++ -c check13b.cpp

clean :
	rm *.o *.out
