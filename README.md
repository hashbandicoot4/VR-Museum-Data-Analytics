# VR-Museum-Data-Analytics

To run this code, save the raw subset from: https://github.com/YunzhanZHOU/EDVAM and the fixation data. 


**Observation 1:**
The user attention is usually aligned with the direction of where their head is pointed.
However turning your head (causing your eyes to move in the opposite direction to your head) may result in the latter values.

![image](https://user-images.githubusercontent.com/72916490/183541382-c7d7cddf-92a0-4103-a272-c5fe1dd04a75.png)

Anything to the left of 6 in the first graph are points where the eyes are pointed to the left.
The second graph shows that your head and eyes are generally aligned and are usually pointed in the same direction. There is also a spike for when your eyes happen to be looking in a very different direction to where your head is pointed (possibly when the user turns their head). 


**Observation 2:**

![image](https://user-images.githubusercontent.com/72916490/183541415-fb7d78db-8256-484e-b251-752f89771bf4.png)

The angle in which users heads point tend to be random, whereas the position users focus tend to spike in the direction of two planes. 


**Observation 3:**
The first plot shows the original frequency of where users tend to stand. 
The new second plot shows where users are more likely to turn (where their eyes are most unaligned with their heads - where they are more likely to turn and not fixate on an object) indicated by the lighter colours.

![image](https://user-images.githubusercontent.com/72916490/183541441-bba3706a-cf80-4f85-85d2-9628cde01e83.png)


**Observations 4 and 5:**
A higher processing power is required to find these results.
The PoG movement section produces a similar graph to Observation 3, where the darker colours indicate the points where users tend to walk towards where they are looking.
The Vestibulo-Ocular reflex section produces a line graph of the focus change against the head change, which should be a rough straight line if this effect is observed. 
