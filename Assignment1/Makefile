all: Equivalent

Equivalent: Equivalent.cpp
	g++ -o Equivalent Equivalent.cpp

dump: Equivalent
	objdump -d Equivalent.exe > Equivalent_numbers.asm

clean:
	del Equivalent.exe Equivalent_numbers.asm

run: Equivalent.exe
	./Equivalent
