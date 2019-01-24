# P00: A Light Hearted Book
```diff
- Nice idea. All in all, its quite simple, so I expect a nearly perfect implementation.
- I found micro switches for your application. Should be in next week. Use a regular switch for testing in the meantime.
- Pay attention to markdown formatting, particularly in References section where everything ended up on a single line.
- Good job diagramming the system, however, where's the RTC (if you're still using it)?
- More detail on parts of code would be valuable. E.g., how long between switch flips? What kind of response (single, small beep or huge annoying alarm) occurs when they haven't flipped a page fast enough? How do they stop reading, or do they have to read forever as long as they own this device? 
```
**Author(s)**: Brian Cox and Kaleb Robinson

**Google Document**: https://docs.google.com/document/d/1FxUdqYAApktBjegVLewhbV0h1axUhUuKEqjMwdc3cTM/edit?usp=sharing

---
## Purpose

We want to create a system that will alert the user that they havent flipped a page in a while. 
Reminding them to read more and in a timly manner. This system will include a feather/very sensitive
switch to sense when a page is being turned. It will then reset a timer tjhat will, when ended, 
will sound a buzzer until the user reads more.

## Initial Design Plan

Outline:
- Parts: Arduino for the board, buzzer, Feather switch
- Parts of code:
  -Loop of timer
  -while statement that checks when the switch is flipped
  -initial setup
  

**Feather Book**:

![Initial Design of how its made](images/featherbook.PNG "Feather book design.")


## Files

- images: showing all the images needed for documentation and showing how it will be made
- licence: All the copy right stuff
- ReadMe: all the documentation and information of the project
- FeatherBook: Where we will be adding the code to make the project work
- ReaMeExample: how to do the ReadMe on our project

## References
https://www.instructables.com/id/Arduino-Aquaponics-Real-Time-Clock-Part-I/ - how to attach clock
https://github.com/PaulStoffregen/Time - sample time library
http://docs.macetech.com/doku.php/chronodot_v2.0 - main time code example

