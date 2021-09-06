SRC = main.c\
src/operations.c\
src/unity.c
INC = inc
all.exe : $(SRC) 
	gcc  $^ -I$(INC) -o $@
run : all.exe
	.\all.exe
clean: 	
	del all.exe