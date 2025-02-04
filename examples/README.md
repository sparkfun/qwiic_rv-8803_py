# Sparkfun RV8803 Examples Reference
Below is a brief summary of each of the example programs included in this repository. To report a bug in any of these examples or to request a new feature or example [submit an issue in our GitHub issues.](https://github.com/sparkfun/qwiic_rv8803_py/issues). 

NOTE: Any numbering of examples is to retain consistency with the Arduino library from which this was ported. 

## Qwiic Rv8803 Ex1 Set Time
This example shows how to set the time on the RTC to a custom time.

## Qwiic Rv8803 Ex2 Print Time
This example shows how to print the time on the RTC.

## Qwiic Rv8803 Ex3 Set Hundredths
This example shows how to set the hundredths register through the I2C interface.
 The hundredths register will be reset to 0 every time the EVI button is pressed.

## Qwiic Rv8803 Ex4A Alarm Interrupt
This example shows how to set an alarm and make the RTC generate an interrupt when the clock time matches the alarm time.
 The INT pin will be high (~3.3V) until real time matches alarm time when it will go low (~0V).

## Qwiic Rv8803 Ex4B Countdown Interrupt
This example shows how to generate a periodic interrupt signal, 
 as well as show you how to calculate the proper set up values for your necessary time.

## Qwiic Rv8803 Ex4C Periodic Interrupt
This example shows how to generate a periodic 1s interrupt pulse

## Qwiic Rv8803 Ex5 Timestamp
This example shows how to get the timestamp of an event generated on the EVI pin, by a button press on the RTC.

## Qwiic Rv8803 Ex6 Fine Tuning
This example shows how to calibrate the RTC's oscillator to have it keep even more accurate time

## Qwiic Rv8803 Ex7 Print Epoch
This example shows how to print the epoch time from the RTC.

## Qwiic Rv8803 Ex8 Set Epoch
This example shows how to set the epoch time for the RTC.


