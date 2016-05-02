Summary:
What I will try to achieve with my final project is to create three interactive, humidity-reponive, and movement-responsive 3D printed planters that will have real plants inside.  The idea is for the planters to show visual feedback of how much humidity a plant's soil has through three different LED light colors, lighting the planters at the end.  Green will represent the plant's soil is humid, and dosn't need water.  Yellow will represent the plant's humidity levels are fine for now, but it's almost time to water it.  Red will represent the plant's humidity levels are low and needs to be watered ASAP.  The planters will also be reponsive to the movement around them; the lights will only turn on if there is movement, and turn off if there is nobody around (subject change by building upon the idea through further research).

Component Parts: I will need plastic to 3D print the planters (plastic will be bought, planters will be made).  Three different colors of LED strip lights, green, yellow, and red (bought). Three small plants (bought).  As wel as an Arduino kit.

Challenges:  I consider the hardest chanllenges might be 1. succesfully 3D printing 3 different planters from scratch, as I've never touched a 3D printer before.  2.  Buidling the code that will succesfully detect the soil's humidity, and being able to determine what is considered too little moisture and what is considered just enough.  3. Make the planters light up depending on movement, again because I've never worked with anything like it.

Project Timeline: I hope to be fully informed on how to use and operate a 3D printer, along with starting to research my code by  week 1.  Have the planters ready by week 2, and start to play around with my code that changes light colors, and detects movement to turn on/off lights between week 2-3.  Have everyhing mostly fleshed by week 4, adding the final touches.  Have everyhing (hopefully) completed by week 5.  

_____________________________________________________________________________________________________________________________
UPDATED 5/2/2015:

Summary:
What I tried to achieve with my final project was to create an interactive, humidity-reponsive, and movement-responsive 3D printed planter that worked with a real plant.
The idea was to use different colors of LEDs integrated in the planter to show whether the plant was thrirsty (dry soil), had enough water (moist soil), or was over-watered (overly-moist soil).   

- Green represents the plant's soil is humid, and dosn't need water.  
- Yellow represents the plant's humidity levels are too high, and might damage the plant (usueful for when you don't know how much to water it).  
- Red represents the plant's humidity levels are low and needs to be watered ASAP

The planter also integrates a distance detector sensor that is connected to the code that changes the different LED colors.
The lights only turn on if there is movement wiithin 20 inches around of the sensor, and turn off if there is no movement around it.

Challenges:
One of the biggest challenges I had was trying to figue out a way to stabilize the feedback of the levels of moisture given through the diffeent colored LEDs.  I would have to change values of the levels that represented all three different states, beceause even though at one point the reading and feedback of the moisture levels might have been consistent, later on I would have to change the values of the levels again in order to be able to match waterver level of moisture it really had.  Ex. The soil would be dry, I'd water it, it would turn red, then I would water it more and it would turn yellow.  A day later the lights would turn red even though the mosiure was fine, or the the lights would be yellow even though they were supposed to be green or red.  I later came up with stable values for all three different states of moisture, but also came to the conclusion that the environment's humidity might be a variable directly affecting the feedback given.

Trying to make a movement sensor functional with the changing of the LED colors was also challenging. At first I started with a complete movement detector that reads all the movement around it.  As I played around with its functionality and its code, I came to the conclusion that a distant sensor might be more appropiate for my concept.  Unlike my first idea, where the LEDs would turn on regargless of any minor moevement around it, the distance sensor would make the LEDs turn on only if a human closely approcahes the plant.  This removes distactions for the user, and makes the planter save eneregy.

Lastly, I wasn't able to add the 3D planter aspect to the project on time due to complications with the 3D printers in the hybrid lab.  Every time I would print there would be some kind of problem with the printer, or would be busy; I tried for almost 2 weeks.  I did print a small model, but not big enough for my plant to go in, an for the LEDs to be wrapped around it.



Link to pictures, video, & schematic:
https://drive.google.com/a/cca.edu/folderview?id=0B_zJX6tgCajoLTkxS0JSMlAwajg&usp=sharing
