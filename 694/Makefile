CC  = gcc
LD  = gcc
OBJ = collatz
LFLAG = -g -lm -lcrypt -O2 -pipe -DONLINE_JUDGE

$(OBJ): $(OBJ).c
	$(CC) $(LFLAG) -o $(OBJ) $(OBJ).c

clean:
	rm $(OBJ)