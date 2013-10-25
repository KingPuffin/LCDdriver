# LCDdriver
Library for working with the LCD screen in the black box via MSP430.
Functionality performed through main.c.

## General Notes
Contains the main.c, a lcd.h, and a lcd.c file.

## Functions
- 'void initSPI()'
  -fe
- 'void LCDinit()'
  -
-void LCD_write_4( char byteToSend );
  -
-void LCDtop();
  -
-void LCDbottom();
  -
-void writeChar( char charToWrite );
  -
-void writeString( char string[]. int stringLength )
  -
-void scrollString( char string[], int stringLength )
  -
-void writeDataByte( char dataByte )
  -
-void writeCommandNibble( char commandNibble )
  -
-void writeCommandByte( char commandByte )
  -

