infinite_loop:
	ca65 --cpu 6502 -o loop.o -l loop.lst loop.asm
	cl65 -C firmware.cfg -m firmware.map -o firmware loop.o ../cc65.lib

clean:
	rm -f firmware *.o *.lst *.map
