What actually worked and failed on the Mutable clones.

* I worked on 3 modules

  * Veils

    * This one at first had weird resonance and clipping on channels 3 and 4. I found that two diodes were reversed. I was able to correct one, but the other flew off into my lab, never to be found. I have to order more. Until then, I don't know if that is the only problem. 
  * Blades

    * I could get audio to pass through, but none of the filtering worked. All the voltages were in normal range on across all the IC's. Filter change (from lpf->bp->hp) on the right-hand stage produced -10V<=V\_f<=+10V. Filter change on the left-hand side amplifies the signal. Square wave into the left-hand filter produced a triangle wave while probe is attached to IC. Frequency on the main out (which sums the two filter outs) is about 200Mz, while frequency on Left out (left-hand filter) is 1kHz. Unfortunately, I did not write down the input amplitude and frequency of the square wave. It was likely 10V\_pp at 1kHz. 
  * Marbles

    * I have not tested as I still need to flash in firmware and don't understand how to test before soldering on pots. 
* The design voltage for the breaker is 400V to 500V. 

  * My log is here: "C:\\Users\\tjbis\\Documents\\UAlbany\\Summer Research 2025\\Daily\\Daily Log.txt"
  * You may access that log file. 
* I don't know if I can provide that number. 
* I was trying to sound smart by talking about the plane capacitance. Its something I don't really understand in the context of the breaker. But I know it was important as high current and voltages pass through and exist across the planes. If they were traces instead of planes, it would increase inductance and therefore affect the timing of the switches for ZCS. So being planes, they provide a capacitance, which may or may affect the timing as bad. 
* The daily log should detail the design process. 

