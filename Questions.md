### Why can you only use certain pins for analogWrite()?
I suspect that it has to do with different PWM frequencies, but I am unsure about the answer.

### What is the range the map() function maps the value to? Why this range?
In the example, the map() function maps the read value to 0 - 255, because it is the maximum range of analogWrite.
