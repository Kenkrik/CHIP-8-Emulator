# CHIP-8 emulator made with C and SDL2
- IBM logo now renders properly
- still need to implement remaining opcodes
## Requirements to build:
- a proper terminal or WSL2
- SDL2, SDL2_image, gcc or some othe C compiler



## To build run: 
    git clone https://github.com/Kenkrik/CHIP-8-Emulator
    cd CHIP-8-Emulator
    gcc -lSDL2 -o CHIP-8 chip8.c

## Run the emulator from terminal and choose the specific ROM file:
    ./CHIP-8 path/to/the/ROM/file

## Example:
    ./CHIP-8 roms/IBM\ Logo.ch8
