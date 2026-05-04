# Homework on Heat, Electric, and Kinetic Energy
In the following assignments:

  * Use $10 m/s^2$ for g, except when otherwise indicated
  * Show the work that arrives at your response. 
  * Use scientific notation for large and small values.  Learning to do this is one goal of the assignment.
  * When relevant, round answers to 3 digits.  
  * In all work, use $\tau$ rather than  $\pi$.  Use $\tau$ instead.
  * In all work, express angles in radians.

### Basic

1. So let's start with the promised experiment to heat Lake Erie (volume $4.84x10^{14}L$) with a 1 megaton detonation, presumably under water so that all the energy transfers to the lake as heat.  How much will the lake temperature rise?

**Ans: $4.2e18/4.84e14J = 8678 J/kg;  8678/4184 = 2.07 \degree C$**

2. Answer the same question for that detonation in a volume of air 10km on a side.  (Density of air is $1.23 kg/m^s$).  That volume of air is about twice the volume of Lake Erie, yet you should arrive at a much greater temperature increase.  Explain why -- there are two major reasons.

**Ans: $4.2x10^{18}/1.23(1x10^4)^3 = 3.415x10^6 J/kg; 3.415x10^6/1000 = 3,415 \degree C$**

**Increase is higher due to lower density of air and to lower specific heat of air.**

3. Compute the thermal mass of the water in a 200L water heater and show that value, with correct units.  

   Using this thermal mass figure, compute the cost to heat the water 30C via electricity at $\$0.15/kwh$ and via gas at $\$1.25/therm$. Assume the electrical power translates to heat directly since the heating element is immersed in water, while the gas is only 70% efficient since some heat is lost to the exhaust going up the chimney pipe of the water heater.

   Assuming the electric version of the heater is plugged into a 240V socket, delivering 15A, how long will it take to heat up the water?  Assuming the gas heater runs at 40,000BTU/hr (that's how they're rated -- you get to translate that to useful units) how long will it take?

   a. Thermal mass:\
   b. Energy to heat by 30C:\
   c. Electric cost:\
   d. Gas cost at 70% efficiency:\
   e. Electric heating time:\
   f. Gas heater power in useful units:\
   g. Gas heating time:

**Thermal mass is $200(1484) = 2.97x10^5 J/\degree C$**\
**Heating by 30C requires $(30)2.97x10^5 J/\degree C = 8.9x10^6J$**\
**Electric cost: $8.9x10^6J/3.6x10^6J = 2.47kwh = \$0.37$**\
**Gas cost: $8.9x10^6J/((.7)1.055x10^8J)=.121therms = \$0.15$**\
**Electric heating time: $8.9x10^6J/(240(15))W = 2472s = 41.2min$**\
**Gas heater in watts: 40,000 BTU/hr = 40000(1056)/3600 =  11,733W**\
**Gas heating time: 8.9x10^6/(.7(11733)) = 1084s = 18min**

4. A Li-ion battery masses 10kg and can deliver electrical power at 30V and 25A for 4 hours. (This amounts to several kwh, as you'll find.)

   * If the energy in the battery is used to lift the battery against gravity, how far up can it lift itself with its own energy? 

   * If the energy instead accelerates the battery horizontally, how fast can it make the battery go, ignoring air resistance?

   * Gasoline has an energy of $4.45x10^7J/kg$.  How does this compare with the energy per kg of the battery?

**Energy in battery = $30(24)(4))(3600)J = 1.08x10^7J$**\
**Lift requires 100J/m so 1.08x10^5m or 1080km**\
**KE is $(.5)(10)v^2 = 1.08x10^7; v^2 = 21600000; v = 1470m/s$**\
**Battery has $1.08x10^7/10 = 1.08x10^6J/kg$** Gas has 41-42x the J/kg**

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


