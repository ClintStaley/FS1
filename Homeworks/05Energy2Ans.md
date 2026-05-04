# Homework on Heat, Light, and Sound
In the following assignments:

  * Use $10 m/s^2$ for g, except when otherwise indicated
  * Show the work that arrives at your response. 
  * Use scientific notation for large and small values.  Learning to do this is one goal of the assignment.
  * When relevant, round answers to 3 digits.  
  * In all work, use $\tau$ rather than  $\pi$.  Use $\tau$ instead.
  * In all work, express angles in radians.

### Basic
1. An airliner travelling at 35,000 feet can move s


### Bronze
5. A hydroelectric dam has water at a height of 150m.  This water drives a generator at the base of the dam, and flows through the generator at 300m^3/second.  How many joules of energy does each m^3 of water provide, and what is the power output of the generator, assuming it's 80% efficient?

    Water supply reservoirs are sometimes drained almost dry during droughts.  But power reservoirs are often maintained near full, even if it means drawing less power from them during droughts.  Why does this make sense, in terms of effective use of the resource?

**Water dropping 150m provides 1500J/kg or 1.5x10^6 J/m^3.  Flowing at 300m^3/s, we get $1.5x10^6(300)(.8) = 3.6x10^8W**

6. Order these three things by thermal mass, from high to low, giving their actual thermal masses.  1) A 500ml bottle of water 2) a 2kg cast iron paperweight 3) the air in a 2mx2mx2m room.  

**Air: $8m^3*1.23kg/m^3(1000J/kg \degree C) = 9840  J/\degree C$**\
**Water: $.5kg(4184J/m^3 \degree C) = 2092J/ \degree C$**\
**Iron: $2(450J/kg \degree C) = 900 J/ \degree C$**

7. You make an igloo that is 500cm thick and 1.5m in radius.  Assuming heat loss through the thick snow below you is negligible, the only heat lost will be fron the half-sphere of snow of thermal conductivity .1 comprising the igloo.  Recall that the area of a full sphere is $2\tau r^2$.  Outside, it's -40C, but you want an internal temperature of 0C, which is liveable with good clothing.  How many watts of power do you need in the igloo to do this?  (And, note, you personally generate 100W of power moving around inside it).  

**Area: $(6.28)1.5^2(.1)(60)/.5 = 170W$**

### Silver

8. You are building a makeshift shelter of 20cm thick styrofoam (thermal conductivity .033).  Assume it's a cube, and you must insulate all 4 walls and the floor and ceiling.  Assume also you want to keep it a comfortable 20C with outside temperature -10C, using only your body heat of 100W.  How big can you make it?

   Just to be sure, you add a small 500W space heater in the shelter you just designed.  How hot will it get now?  Realizing that's pretty hot, you reduce the styrofoam thickness to return to 20C.  What thickness is that?  Do both of these calculations by simple reasoning and a bit of math.  Do *not* redo the full thermal conductivity computations!

**Per m^2 of 10cm styrofoam we have $(30)(.033)/.2 = 4.95W/m^2$, so we can afford 100/4.95 = 20.2 m^2 or 3.37^2 per side.  Size is $\sqrt{3.37} = 1.83m$ on a side**\

**Space heater increases wattage by x6, so temperature difference can also be 6x, or -10 + 30*6 = 170C.  Repair this by reducing thickness by x6 to 3.33cm**

9. You're wiring a high-amp 30A wall socket from a breaker box, with a 30A breaker at the box, and the socket is 15m from the box.  Code demands 10-gauge wire for this application, but all you have is 20-gauge, which is a lot easier to bend, and you figure code is for sissies. (Higher gauge is thinner wire.)

    A 15m run of 20 gauge wire has 0.5 ohms of resistance.  If you pull the full 30A at the plug, what do you expect the voltage drop to be from the box to the plug?  What will the remaining voltage be at the plug, assuming 120V at the box?  And, what wattage is consumed in the wire as heat?  Is this a good idea?

**15V/.5ohm will drive 30A per ohms law.  So you'd expect 120V-15V = 105V at the outlet.  That's bad enough.  But 15*30 = 450W of power in the wire, which will heat it considerably.  Bad idea**

10. Copper has a conductivity of roughly $6x10^7 \frac(A m){m^2 V}$.  From this fact, and the statement above that 15m of 20 gauge wire has 0.5 ohms of resistance, deduce the cross-sectional area of 20 gauge copper wire, in square millimeters.  (You should arrive at a value < $1 mm^2$).

    a. How many A/V does 0.5 ohms indicate?  
    b. How many $\frac{A m}{V}$ is that, given the 15m run.
    c. What would the $m^2$ value in the conductivity then need to be to arrive at conductivity of $6x10^7$?

**$0.5\Omega = 2 \frac{A}{V}$**\
**Through 15m, that's $\frac{30 A m}{V}**\
**$6x10^7 = \frac{30}{m^2}; m^2 = \frac{30}{6x10^7} = 5x10^{-7}m^2 = .5 mm^2$


