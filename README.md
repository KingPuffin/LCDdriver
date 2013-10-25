# LCDdriver
Library for working with the LCD screen in the black box via MSP430.
Functionality performed through main.c.

## General Notes
Contains the main.c, a lcd.h, and a lcd.c file.

## Functions
- `void initSPI()`
  - Initializes the SPI for the chip
- 'void LCDinit()'
  - Initializes the LCD Screen
- `void LCD_write_4( char byteToSend )`
  - Given a char, writes 4 b
- `void LCDtop()`
  - Switches to the top line of the LCD
- `void LCDbottom()`
  - Switches to the bottom line
- `void writeChar( char charToWrite )`
  - Will write a char to the Screen
- `void writeString( char string[], int stringLength )`
  - Writes a string of chars to the screen
- `void scrollString( char string[], int stringLength )`
  - Scrolls the screen by moving the first char to the
  - last spot of the string and shifting every other char
  - up one
- `void writeDataByte( char dataByte )`
  - Used to write bytes to the screen
- `void writeCommandNibble( char commandNibble )`
  - Used to write a nibble, useful for Pins
- `void writeCommandByte( char commandByte )` 
  - Writes a byte. Useful for interfacing with the screen

