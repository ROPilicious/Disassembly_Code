# capstone library name (without prefix 'lib' and suffix '.so')
LIBNAME = capstone

capstone_disassembly: capstone_disassembly.o
	${CC} $< -O3 -Wall -l$(LIBNAME) -o $@

%.o: %.c
	${CC} -c $< -o $@