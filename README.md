# Barcode-Title-Reveal
Barcode to Title formation during inauguration

#throwback-april-2024

It was the first time conducting a Techno-cultural fest alone by my Department(ECE). The name of the fest was 'ELECTRA' and since it's the first time happening something like this we all wanted it to be different from other's as possible, so we came up with a lot of ideas and events. This is one of it.

After a lot of thinking about the title display as a part of inauguration, this barcode idea was formed. Even though it looks nothing complex, a lot of effort has put into this.

Before 👇

![img alt](https://github.com/Anandhu-Sudha/Barcode-Title-Reveal/blob/b8478a8c827190e270fd19fada85c7808052bf87/pictures/before.png)

After 👇

![img alt](https://github.com/Anandhu-Sudha/Barcode-Title-Reveal/blob/b8478a8c827190e270fd19fada85c7808052bf87/pictures/after.png)

Video 👇

https://github.com/user-attachments/assets/9bb26b52-7236-4a16-a0af-d504ff39dbe8

<b>Construction</b>
-------------------

The letters 'E'L'E'C'T'R'A' has been cut out from a material called 'Forex' and the Vertical parts are kept stationary while the other parts are attached to a sg90 servo motor. 15 servo motors are used in this. 


After the completion of structure 👇

https://github.com/user-attachments/assets/98e9c65f-6ee3-4c3b-8d17-26167cb86a5d

<b>Coding</b>
-------------

can be only attained after so many rounds of trial and error. to find the 15 servo's vertical angle and the angle I wanted. after finding the angles for each servo I noted it down and in the coding part it was added.

Checking for the first time 👇

https://github.com/user-attachments/assets/86952201-222d-4731-87bb-74555898ba7e

After coding the half blocks 👇

https://github.com/user-attachments/assets/f50748d2-2aad-46dd-861c-0c3df61a7b61



<b>Challenges</b>
-----------------

Since there was only 13 digital pins in UNO , i tried connecting the rest to the analog pins but it was not working as expected somehow. there was no time to experiment or study in detail. 

So i thought about adding another UNO and trigger the second UNO when it's time. 
'E'L'E'C'T'R' After these letters are formed for the 'A' a signal from first UNO is given to second UNO then second UNO controls the 'A'. This was the plan, but it also failed. i was about to give up. In the last moment i luckily got a Arduino MEGA from the college and it worked like a charm... Everything was perfect.

Of course we can't run all this servos from the Arduino's power and we also didn't want that. We needed it to form the letters sequentially. So that problem solved there.

Final view 👇

https://github.com/user-attachments/assets/cb09b351-3006-4354-916b-0560b1cf724b

Some paint touch ups were pending....

Note* - The small vibration after servo rotation was due to lack of current (since it was powering from the laptop)

Even though it was working fine.. i was nervous at the time of inauguration, when the college chairman cut the ribbons and i turned on the trigger switch... phew.. it worked... that was such a relief 😅... 

Videos and Pictures are added.
