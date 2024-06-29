# Electronic-birthday-greeting-card

# Nerdy electronic birthday greeting card using Arduino Nano.

The Electronic Birthday Greeting Card is designed to surprise and delight the recipient with a special birthday message displayed on an OLED screen, accompanied by LED lights and a buzzer playing a birthday tune.

Initially, the date will be displayed, followed by an introductory animation of a cat. Then, it will display 'Happy Birthday XYZ'. Simultaneously, the happy birthday tune will be played.

After the tune is completed, an instruction to blow on the microphone will be displayed. Once the recipient blows on the microphone, the LED lights will turn off, representing the blowing out of the candles on a birthday cake.

This will be followed by an outro animation, and a message will be displayed (at least once every 5 iterations). The message will be selected randomly from an array of messages.

All the messages and birthday wishes can be modified in the code accordingly.

## Parts required:
1) Arduino Nano
2) 0.96 inch 128*64 resolution OLED display (I2C version)
3) 10K ohm resistor
4) 250 ohm resistor
5) Passive buzzer
6) Yellow led
7) Blank PCB
8) Cake cutout
9) Battery (Use and throw coin battery can be used like CR2032 two in series or lithium ion and lithium polymer battery with charging circuits can be used)
10) Charging and voltage booster (step-up) circuit must be included if lithium batteries are used.
    Example:- TP4056 for charging and MT3608 step up module.
    
Note:
1) While using lithium batteries proper charging mechanisms should be used. Also voltage booster circuit is needed to increase the max 4.2V of lithium battery to 5V as input for arduino. Small powerbank modules can be used as they can charge the battery safely and also boosting the voltage to 5V. An extra 100 ohm resistor is connected in parallel to the load so that the powerbank module stays active.
2) The animations used (cat and cross) for intro and outro can be changed and how to change the animations according to personal choices can be done by watching the below tutorial.
   ### Link for the tutorial:
   https://youtu.be/o3PhC_VJdXo?feature=shared


