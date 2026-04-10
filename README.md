# Simple LED Sequencer Circuit

This project is a basic analog LED sequencer using resistors, capacitors, a battery, and a switch. Three LEDs turn on one after another, then all fade out together when the capacitors discharge.

### What it does
LED 1 turns on first                                                                                 
LED 2 turns on after a short delay                                                                   
LED 3 turns on after another delay                                                                 
Once all three are on, they gradually fade out at the same time                                    

The fade-out effect is created by the discharge of capacitors, which reduces the current smoothly instead of cutting it off.

### Components
3 × LEDs                                                                                            
6 × Resistors (for current limiting and timing)                                                    
3 × Capacitors (for delay and fade effect)                                                          
1 × Battery                                                                                        
1 × Switch                                                                                         
1 × Breadboard                                    and some jumper wires

### How it works
sequential-led uses a parallel design, with 3 RC modules each for an LED, each one having the same capacity to match the fade at the end and diffrent resistor values. All this is powered by a standard 5V battery
