# PIC16F1455_Bootloader

PIC16F1455 Bootloader using RA4

Variation of https://github.com/majbthrd/PIC16F1-USB-DFU-Bootloader/tree/master/firmware that uses RA4 to enter DFU Mode


# uses gputils

https://gputils.sourceforge.io/

# assemble it
gpasm -p p16f1455 -DSERIAL_NUMBER=1 -o bootloader.hex bootloader.asm
