SRC = main.c operations.c
INC = fun.h struct.h
all.exe : $(SRC) 
	gcc  $^ -o $@
run : all.exe
	.\all.exe
clean: 	
	del all.exe