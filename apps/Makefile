all: cit citin flashprog modt ddtest setmod ddflash setmod2

cit: cit.c
	$(CC) -o cit cit.c -lpthread

modt: modt.c
	$(CC) -o modt modt.c -lpthread

setmod: setmod.c
	$(CC) -o setmod setmod.c -I../include/

setmod2: setmod2.c
	$(CC) -o setmod2 setmod2.c -I../include/

flashprog: flashprog.c
	$(CC) -o flashprog flashprog.c

ddtest: ddtest.c
	$(CC) -o ddtest ddtest.c

ddflash: ddflash.c
<<<<<<< HEAD
	gcc -o ddflash ddflash.c

clean:
	rm -rf cit citin flashprog modt ddtest setmod ddflash
=======
	$(CC) -o ddflash ddflash.c
>>>>>>> 933779aa24b643c4bdb72cbf7998eb96b9727084
