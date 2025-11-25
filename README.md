# RISC-V
## Comandos para rodar no seu terminal QEMU + Ubuntu

- nano NAME_FILE.s
- riscv64-linux-gnu-as NAME_FILE.s -o NAME_FILE.o
- riscv64-linux-gnu-gcc -nostdlib -static NAME_FILE.o -o NAME_FILE
- qemu-riscv64 NAME_FILE; echo $?

