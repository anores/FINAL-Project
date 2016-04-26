Every time you run in to unexpected behavior in your project (a bug, a component that works differently than you thought, or something else), make an entry in your log. Describe the following:

1. In a sentence, explain the behavior you expected.
2. In a sentence, explain the observed behavior.
3. Formulate a hypothesis about what might be causing the mismatch: what part of your code or what part of your circuit is behaving in a way you don't expect?
4. Test your hypothesis: what action can you take you determine if your hypothesis is true?
5. What is the result of your test?
6. Repeat steps iii-v above until you resolve your "bug".

LOG: 

-Come up with idea for project - 3D printed planters that detect moisture level & give feedback through 3 different LED light colors.  Colors are intractive through motion detection.
-go to hybrid lab to talk about my idea, and what components/software I might need.
-order 1m LED color strip.
-research/come up with:
-if(analogRead(5)<350){
-if(analogRead(5)>350&&analogRead(5)<700){
-if(analogRead(5)>700){
-print "I am thirsty please give me water" on <350 for my reference 
-print "I feel so comfortable" for my reference" on >350 & <700
-print "Too much water, I might get hurt" >700 for my reference
-// This is for Trinket 5V 16MHz, you can remove these three lines if you are not using a Trinket
  #if defined (__AVR_ATtiny85__)
    if (F_CPU == 16000000) clock_prescale_set(clock_div_1);
  #endif
  // End of trinket special code
-strip.show(); // Initialize all pixels to 'off'
-strip.setPixelColor(i, 255, 0, 0);   //turn every third pixel off /RGB // LED COLOR = red
-strip.show(); //Tells it to run
-strip.setPixelColor(i, 0, 255, 0);  // LED COLOR = green
-strip.setPixelColor(i, 255, 255, 0); LED COLOR = yellow
4/25/16 -had error message: arduino board at /dev/cu.usbmodem 14 is not available
-switched ports-worked
-LEDs would not change to green even though it's in relatively moist soil
-lowered I feel comfortable analog read to 200-not working 
-lowered I feel comfortable analog read to 170-not working 
-lowered I feel comfortable analog read to 150-not working
-lowered I feel comfortable analog read to 170-not working
