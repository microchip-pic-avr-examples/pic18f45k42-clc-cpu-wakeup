# CLC for Complex CPU Wake-up Conditions
This example uses the CLC to create a combinational logic to wake up the CPU

# Description
This example uses the Configurable Logic Cell (CLC) to create a combinational logic to wake up the CPU. The following logic is generated to achieve the wake-up condition. Therefore, only when the POT voltage level is higher than the Fix Voltage Reference (FVR), and either of the pushbuttons are pushed, the CPU will be waken by the CLC interrupt.
![](https://static.transim.com/img/82018/f1772c4d5ecc40b6892bb6d7dd0b3672-f0l0g.png){width=auto height=auto align=center}


# Result
When the wake-up condition is achieved, the LED will light up for a while and the CPU will go back to Sleep Mode afterwards.

This example is demonstrated in the livestream "Think Outside the CPU: MCU Signal Processing Without Using the Core". Check out [the livestream](https://www.youtube.com/watch?v=MK0ci7FHcdc&feature=youtu.be) for more information.