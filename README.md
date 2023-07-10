# Stop Watch System
The stopwatch System implemented on an AVR microcontroller uses a timer and external interrupts to control the stopwatch display on a 7-segment display in addition to reset, pause, and resume functions.
The application uses a timer to generate an interrupt every second and updates the displayed stopwatch value accordingly. The application also uses external interrupts to reset, pause and resume the stopwatch.
The application uses three external interrupts, INT0, INT1 and INT2, to perform different functions on the stopwatch. INT0 is used to reset the stopwatch, INT1 is used to pause the stopwatch, and INT2 is used to resume the stopwatch.
The application uses Timer1 in CTC (Clear Timer on Compare) mode to generate interrupts every second.


**Demo**
![](https://github.com/husseinAhmed10/Simple-Calculator/blob/main/Stop-Watch.gif)
