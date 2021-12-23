# BMSselect

This board is calibration of the BMS units. It uses dpdt relays to connect individual cells in a battery module (up to 18 cells) to an output where a high accuracy voltmeter can be connected.

A STM32F410RBT6 is used to control the relays, and seral-usb communication to a PC. The PC can control the cell selection to the voltmeter and read the voltmeter readings along with the BMS board readings and compute a calibration parameter for each cell.

