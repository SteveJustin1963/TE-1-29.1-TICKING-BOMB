# TE-1-TICKING-BOMB

https://easyeda.com/editor#id=143baa6ba49f4032a876b9fd3404e58b

![](https://github.com/SteveJustin1963/TE-1-29.1-TICKING-BOMB/blob/master/tick-bmb-cct.png)

The TICKING BOMB, for instance, is ideal as it uses both an NPN and a PNP transistor so that either one can be substituted with an unknown type. As a precaution against reverse voltage you should include a 1k resistor in series with one lead of the battery. This will limit the reverse current to 10ma while the electrolytic reduces the impedance of the supply to enable the circuit to operate. 

When you build this circuit you will see what we mean. The effect from the speaker is very similar to a loud ticking clock. The 100mfd electrolytic is very important. It reduces the internal impedance of the battery (especially if it is low) and changes the tone from a soft tick to a very loud sharp click. It also reduces the current from 25mA to about 2mA. The circuit operation is very simple. On connecting the battery the 10k resistor, 200k pot, 2.2uF capacitor and 8 ohm speaker are the only parts drawing current. As the capacitor begins to charge the base voltage on the NPN transistor rises to about .6v This turns the transistor on and in turn switches the second transistor to a conducting state. This results in a click from the speaker. At the same time the negative lead of the electrolytic is brought nearer the positive rail and thus the charge on the electrolytic is reduced. This turns off the first and second transistors to begin the cycle over again.  The rate of charge of the electrolytic is dependent upon the value of the resistors in series with it. Thus the rate of ticking can be altered by the trim pot. Almost any NPN and PNP transistors can be used in this circuit. In fact this circuit is an ideal simple test for transistors. It will determine if they are NPN or PNP. All the parts are mounted on a small piece of veroboard 15 holes by 15 holes. 
## Parts
* transistor BC 547
* transistor BC 557
* resistor 10k
* electro 2.2uF 6v
* mini-trim pot 200k
* electro 100uf 16v
* 2-1/4" speaker 8 ohm
* 9v battery
* battery clip
* piece of veroboard 
