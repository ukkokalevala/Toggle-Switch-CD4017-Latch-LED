Project 
One-Button ON/OFF LED Circuit 
________________________________________
Briefing
This project demonstrates a simple ON/OFF toggle using a push button and a CD4017 decade counter IC, without using any microcontrollers.
How it works:
• The CD4017 counts the number of button presses. 
• The first press activates the LED (turns it ON). 
• The second press resets the output, turning the LED OFF. 
• A resistor and optional capacitor clean the button signal to prevent false triggering from switch bounce. 
• This creates a hardware latching effect, storing the LED state in the IC without software. 
Key components:
• CD4017 Decade Counter IC 
• Push button 
• LED + current-limiting resistor 
• Pull-down resistor (10kΩ) 
• Optional capacitor (100nF) for debouncing if needed 
Applications:
• Simple ON/OFF switches 
• Hardware toggle indicators 
• Learning basic digital logic and flip-flop behavior
Schematic
