# FS 1 lecture outline

## Syllabus
### Goals of class
   • Demonstrate, by reasoning from physics principles, *intuitive understanding* of a variety of aspects of classic physics, e.g. kinematics, linear and rotational motion, forces, energy, collisions, gravitation, wave motion, and simple fluids.
   • Apply physics concepts to understanding practical areas such as aerospace, electrical power, transportation, communication and the environment.
   • Use physics concepts and approximate mathematical reasoning to gauge the accuracy of scientific or technological statements.
   • Apply the history of science and technology to understanding current issues in science and tech.
   • Use metric units directly and intuitively, not just by translation from SAE units

### Rules of Note
   * Quizzes and LLMStudies
   * HW levels and fully complete work
   * Wearing the badge!

### Units
   * Metric universal outside US and in US science.
   * Use *intuitively*; I'll provide translation but we'll just "talk in metric" in class
   * meter (yard + 10%), kilogram (2.2lbs) (1L of water)

## Topic 1 Motion
### Motion basics: distance, velocity, acceleration
 * Why motion?  Good basic physics.  Core of Newtonian Physics.  Challenge historically (Aristotle and violent vs natural motion) Example of precise mathematical understanding of a natural phenomenon.
 * Basic concepts: Position, speed, (vs velocity), acceleration
   * Units? (ask them: meters, meters/sec, meters/sec/sec or meters/sec^2) 
   * Gut check: Running speed?  Car speed.  (Trick: m/s*9/4 = mph)
   * instantaneous vs average. If Joe runs 100m in 20 seconds, he averages 5 m/s.  Is that his speed the entire 20 seconds?
   * If we accelerate by 4 m/s^2 for 5 seconds, how fast are we going?
      * 20 m/s or 45mph
   * And, how *far* did we go?? 5s*20m/s = 100m??
      * no, because we averaged half that during the 5 s, so 50m
   * How much acceleration *is* 4 m/s^2?  (Well, enough to go from 0 to 45 in 5s)
   * "gravity" is 9.807 m/s.  We'll use 9.8.  (Varies from 9.83 down to 9.76 -- why?)
      * Can measure acceleration in "G"s.
   * Can position, speed, acceleration be negative?  What does that mean?
      * position before starting point
      * speed in opposite direction
      * deceleration
 * Drawing some exact graphs
    * time across X axis, 0 to 8
    * Distance graphs
       * Steady V of 2 m/s
       * V of 3m/s for 2s, then steady, then backwards at 1 m/s
       * Sudden jump ?  Can we have instant change in distance?
    * Velocity graphs
       * Steady acceleration of 4 m/s^2 for 5s
       * A of 2 m/s^2 for 2s, then level, then -1 m/s^s for 4s
       * Carry further out past 4s to get negative speed
       * Sudden jump possible?  Might seen so, but even an explosion involves some time.
    * Relationship between distance and V graph
       * Use initial example and argue that distance is area under curve
       * Second example... Does height of level area matter?
       * What about negative speed?  Negative area below curve.
    * Acceleration graphs
       * Steady A of 4 m/s^s for 5s, then zero
       * Instantaneous jump *is* possible!
       * Area under curve is v.
       * Second example. v runs up, then down, then negative
     * All three in one
       * steady A of 1.5 m/s^2 for 8 s
         * V goes up to 12 from 0 (area under a curve)
         * D goes from 0 to 48, but what shape?  Suss this out.  
           * Slope is steadily increasing.. 
           * At a given time t, v = at.  D under curve is triangle area (at) t
           * at^2/2
           * Try for t=4. v = 6, d = 12
           * d is parabola
       * Car moves through two lights and a speed limit change
         * 30s in 5s
         * a is zero, but initial v is 15m/s.  A is zero for 5s, then -5 m/s^s for 3, then 0 for 10, then 3 m/s^2, then 0 for 5, then -3 m/s^2 for 2, then 0
         * distance is area under curve...
       * Ball thrown up at 19.6m/s^2 for 1 s

 * Concept of surge, jerk, or jolt
    * What units?
 * Classic thought didn't really understand acceleration as a concept.

### Mass and Forces
 * Now we deal with what *causes* acceleration -- forces.
   * car engine turning wheels; brakes slowing
   * hand pushing ball up; gravity pulling it down
 * Rule 1 (aka Newton's first law)
   * No force, no acceleration
   * Example of ball in free space moving at 20 m/s.  Will go foreve
   * But rolling car eventually slows down... ?
      * What force causes that?
 * But is that all?  A given force produces a certain acceleration?
   * Mass also matters
   * twice the force, twice the acceleration.  Twice the mass, half the a, etc.
   * a = f/m.  Newton's second law 
   * or more commonly f = ma, but first form is better if you seek a
 * Mass vs weight
   * KG is *mass*.  Only informally weight.  Exists on surface and in space
   * Example of 1 MT car on earth, on the moon (), on  and in space.
 * Unit of force needed.  Enough to accelerate 1 kg by 1m/s^2 -- a newton.  Deck of cards on hand.
   * So, with that definitions, how many newtons does a kg mass weigh?
   * weight is a *force*.  How hard a thing pushes down on a scale.
 * Most cases have multiple forces
   * So, the f in a = f/m is a *sum* of relevant forces, added like vectors
   * Bit of review on 2-D vector adding
      * Vectors are pairs of numbers, like coord
      * Just add the pairs
      * Try a few examples

#### Examples of force combinations: FBDs
* Falling raindrop, forces balanced, no a
* Object in hand, forces balanced, no a
* Object being lifted or lowered in hand (forces briefly imbalanced -- causes a)
* Object being raised steadily (no a -- forces in balance)
* You in an express elevator, as it starts up, as it's moving, as it slows at top
* Two objects, one 1kg, one .001kg (one gram) falling in vacuum.
   * Force on one is 9.8N, the other .0098N.  So, does the first accelerate more?
      * No because mass and force are in exact proportion.  a is the same for each.
      * 1kg requires 1000 times the force but gets it.
   * Galileo first to understand this.  Famous Leaning Tower experiment
   * https://www.youtube.com/watch?v=Oo8TaPVsn9Y
* Back to card deck being lifted
   * What exact forces, assuming I increase it to .1 m/s up, in .5s?  
   * (a is .2, m is .1kg, so total force f = ma is briefly .02N.  My hand presses with 1.02N)
   * At top, opposite occurs and f of my hand is briefly .98N
* What if forces are in different directions?
   * 1kg ball suspended by 45 degree cables....
   * So, what do we intuitively expect on the cables?
   * Seeing forces as right-angle vector components.  Equivalent
   * Horizontal forces balance...
   * Vertical forces must balance 9.8N
   * Each is 4.9N if balanced
   * 4.9/.707 = 6.93N.  Make intuitive sense??
   * For simple case of 45 degrees, we have .707 in each direction (.707^2 = 1/2..)
* What about a 60 degree angle?  What do we expect, intuitively?
   * Cos and sin review
   * Breakdown of 1/2 and .866
   * Need 4.9/(1/2) or full 9.8N on each
* Brief example of how to design a pin-truss
* Term "Free Body Diagram"
* Friction example w/ inclined plane
   * Draw FBD and see a force is missing if block is stable.  Would it be on ice?
   * Add friction force opposed to slide along surface
   * How friction works
      * Proportional to total normal force into surface
      * Same Newtons no matter how fast the slide
      * Interestingly, not proportional to area of contact.  Why?
         * Normal force is spread over the area.
         * Twice the area with half the force per area is the same
      * Two forms: 
         * static ("stick" force matches other lateral forces up to breaking point)
         * kinetic (while sliding)
      * Thus N (of side force)/N (of normal force) -- unitless ratio "coefficient of friction"
      * Can be .1/.02 for ice on ice; .65/.4 for steel on steel
         * 1kg steel block on steel surface ?? (6.5N to break loose, 4N to keep going)
         * 100kg block on ice? 10N to start; 2N to maintain.
   * Analyze block and ramp
      * assume steel on steel.  What angle "breaks" the stick?
      * angle of ramp is angle of g to normal, by swinging arg.
      * Down-ramp force is .65 of normal.
         * Make a guess.... <> 45 degrees?
         * maybe 30 degrees? Normal is $cos(theta)$ Down-ramp is $sin(\theta)$
            * .5/.866 = .577
         * what angle then? No need for actual force! $sin(\theta)/cos(\theta) = .65$
         * sin/cos is tan, so $tan^{-1}(.65)\approx33\degree)$
      * Good example of type of calc done in intro ME

### Equal and Opposite forces
* When two objects put force on each other -- it's two way.  (push exercise)
* Gravity is same -- two way
* General principle: forces are *paired*
* Newton's third law -- "Every action has an equal and opposite reaction"
* Show force pairs in all our examples
* Deck of cards lift.  
   - Hand<->deck obvious pair
   - Earth<->deck ?? (deck pulls on Earth too)
* Raindrop fall
   - gravity is now dual
   - air resistance ?? (drop pushes on air)
* Hanging ball
   - gravity dual
   - ball pulls on cables and vice versa
   - cables pull on anchors
   - anchor horizontal pulls balance
   - vertical pulls on supports balance push on Earth
* Sliding block
   - Friction pulls slide (which itself has friction on table)
      - What would happen with very heavy block and slippery slide ?? (slide goes right)
   - Normal force balance; gravity balance.  
   - Force of table <-> ramp

### Underlying laws for balanced forces
* Gravity
   - Aside on scientific notation
      - gut feel: x10^6? x10^3, etc..
   - $F = G\frac{m_1m_2}{r^2}$ where $G = 6.67 x 10^{-11}$
   - OK, and we know that g is 9.8.  Try it out for a 100kg mass
      - $980 = 6.67 x 10^{-11}\frac{100 m_2}{(6.38x10^6)^2}$ 
      - m2 = ?  (5.98 x 10^24 kg)
      - Remarkable that we can do this.  Will do for moon and sun after we have a bit more physics
      - If you are in orbit 500km up, what's g then? 
         - No need for full computation -- it's inverse proportional to r, yes?  
         - R ratio is 6.38/6.88 or .927.  Squared is approx .86  
      - What is g at 1 earth radius up?
   - Universal attraction: every particle against every other.  Moon is pulled by and pulls Earth, but also Sun, (and Jupiter, venus, etc.)
   - Newton and apple story: fact vs legend
   - Newton and brachistochrone 
   - Same pattern for electric forces
      - Now positive and negative attract, like repel.  
      - Fundamental charge is that of electron or proton
      - But, we use "Coulombs", which is like a "kg" -- 6 x10^18 electrons.
      - Amount of free electrons in grain of sand copper, or in half a second of electricity in a house wire.
      - And, the constant is: 9x10^9.  Notice a difference?
      - One coulomb imbalance at 1000m distance is 9x10^9/1000^2 = 9x10^3 or 9 metric tons.
   - contact forces are repelling electrons, basically

### Acceleration perpendicular to the velocity
  * Velocity is also a vector.  Force applied to v is not always collinear.
  * Spin weight around.
  * Change that results from acceleration in magnitude equal to force once (3 m/s, acc of 3 m/s^2 at right angles)
     * Turn of radian per second.
  * Making an object follow a circle at circumferential V requires how many R/s?
     * V/r
  * So, need acceleration of magnitude $v * v/r = \frac{v^2}{r}$
  * Intuition
     * r in denominator because larger r requires fewer R/s
     * V squared because twice the v requires twice the R/s and twice the a to turn it.

  * Example of a car going around a corner: max speed that a car can have on a corner of radius 10m.
     - centripetal force needed 
     - force exertable by tires
        - Area matter? Number of tires?
        - $\mu_f = .9$, rubber on dry asphalt
        - car mass 2000kg
        - So, 20000N * .9 = 18000N
        - $m(v^2/10) = 18000; v^2 = 90; v = 9.48$
        - mass of car matter?
  * Washing machine spin cycle
    * 30cm radius; 300 rpm
    * $v^2/r = (5*2*\pi*.3)^2/.3 = 296m/s^2 = 30.2G$ 
  * Geosync orbit
    * R from center of earth; (Earth radius is 6.38x10^6)
    * $v = 2\pi R/(24(3600)) = 7.27x10^{-5}R$
    * $v^2/R = (7.27x10^{-5})^2 R$ = 9.81(6.38x10^6/R)^2$
    * $R^3 = 9.81(6.38x10^6)^2/(7.27x10^{-5})^2$
    * $R = 42.235x10^6m = 42,235km = 35855km above surface$
  * Mass of Sun:
    * Earth 1.5x10^8km or what in m?
       * 1.5x10^11m
    * Time to orbit is 3.1 x 10^7
    * Orbital speed thus? 
       * 30,400 m/s
    * acceleration is?
       * v^2/r = .0062 m/s^2.  Very small!
       * .0062 = G m/r^2 = 6.67x10^-11 * m / (1.5x10^11)^2
       * m = 2 x 10^30 kg

## Topic 2 Energy
* Forms of energy
   * kinetic
   * light/radiation
   * electric
   * potential
      * gravity
      * chemical
   * heat
      * vibration.  Absolute zero.  Kelvin -273

* General conservation of energy
   * Driving a car.  Chemical -> kinetic -> heat
   * Lighting a room: light -> heat
   * Dropping a weight: potential -> kinetic -> heat

* Energy units
   * Joule -- 1 kgm^2/s^2.  
      * Energy to lift one kg one meter against 1 m/s^2 acceleration
      * 1N across 1m, or 10N across .1m, etc.
   * Watt -- 1 J/s
      * Power vs energy
      * Lift 1kg .1m/s
   * Convenient alternates
   * calorie (cal) -- 4.2J
      * Heat 1 gm of water 1C originally and still accurate
      * Formally, 4.184J
      * (5ccs per teaspoon)
      * Book falling .42M in gravity heats 1/5 tsp 1C
   * Kilocalorie (kcal) -- 4184J
      * The "food" calorie
      * Heats 1L of water 1C
      * 15cc oil has 120 kcal.  Burn to heat 2L?
   * BTU and Therm (100,000 BTU)
      * old school "kcal" -- 1lb of water 1 degree F
      * BTU = 1055J
      * Still useful in e.g. gas bills
      * No longer used in Britain!
   * kilowatt-hour
      * 1000W for 1 hour
      * How many J?  (3.6 x 10^6)
   * kiloton
      * Nominally 1,000 tons of TNT
      * Formally, 4.2x10^12J
   * (Note these carefully for homework exercises)
* Kinetic energy
   * If a kg is moving 10m/s, how far up can it go on a ramp?
   * Reason out that it's the square of the velocity
   * Joule = newton-meter, so 1 KG at 10 m/s can rise for 10s at average v of 5.
   * In general, the kg can rise against 1N for V s at V/2 average speed.
   * Kinetic energy is thus v^2/2 for each kg, or $\frac{1}{2}mv^2$
* So, let's do some conversions of energy
   * How much does it cost to heat 1L of water 60C for coffee? ($.15/kwatt hour)
   * Drop 1KG 5m into 10L of water.  How much does it warm up?
   * (Recall $v = \sqrt{2da}$)
   * Fire 10g bullet at 500m/s into 10L of water.
      * Use machine gun to make coffee...
   * Accelerate a 1MT car to 30 m/s electrically with 10KW battery.  How long?  (4.5s)
   * Lift same car up 100km electrically.  How many kwatt-hours?
   * Accelerate car to 8km/s also.  How many kwatt-hours?
   * Heat Lake Erie (4.84x10^14L) with 1MT detonation
      * $4.2e18/4.84e14 = 8678 J/L;  8678/4184 = 2.07 \degree C$
      * Sort of disappointing, but Tsar Bomba (~50MT) would have brought it to boiling.
* Electrical energy
   * amp definition
      * Interesting history on amp definition
   * Volt definition
   * Watt = V*A
   * 15A wall socket at 120V gives? *(1800W)*
   * As a heater, will take how long to raise 2L from 20C to 100C?
      * $80*4184*2/1800 = 372s$ or just over 6 min.
   * Solar energy is about 1kw/m^2.  But cells are maybe 20% efficient, so we'll use $200W/m^2$
* Run a car off solar cells on its roof -- say 4m^2?
   * How much power?  **(800W)**
   * How long to accelerate 1mt to 10 m/s (residential speed)?  1000kg 10^2 1/2 = 5x10^4J
   * 50,000/800 = 62.5s, around a minute
   * So, without recalc, how long to get to freeway speed of 30 m/s?  (x9 so 9 min)
   * (air resistance will actually stop it from getting that fast)
* More on Heat Energy
   * Already discussed joules <-> calories, but is temperature/kg-joule the same for all substances?  
   * Specific heat: $J/kg \degree C$
      * Water?  (4184)
      * other substances: Iron 450; rock 800; air 1000; lead 129
      * You heat a cast iron pot (4kg) full of water (2L) to boiling (+80C).  How many J?
         * **Pot: 80 * 4 * 450 = 144 kJ; water: 80 *2 * 4184 = 669 kJ
         * So, pan weighs twice the water, but uses < 1/4 the energy
      * 1MT goes off in a 10km^3 box of air.  (Air is 1.23 kg/m^3)
         * Mass of air: 1.23x10^12kg.  4.2x10^18J/1.23x10^12kg = 3.4x10^6J/kg = 3400 degrees C
   * *Thermal mass* $J/\degree C$
      * Multiply in the mass to get a whole object's capacity.  
      * Thermal mass of a cubic meter of water?
         * $4184*1000 = 4.18x10^6 J/\degree C$
      * You heat a home with electricity, and have a setup where a m^3 of water gets heated to 60C by sunlight, then releases that heat at night.  How many kwh do you save?  
         * $(60-20)C*4.18x10^6 J/C = 1.67x10^8J$
         * $1.67x10^8 / 3.6x10^6 = 46 kwh$; 46*\$.15 = $6.97/day
      * Thermal mass of small office 3x4x2.5m^3 of air? 1.23*30*1000 = 36900J/degree C
         * 1800W space heater heats 5 degrees?  36900/1800 * 5 = 102.5.
* Heat flow
   * Thermal conductivity $W/m\degree C$
   * Flow is per area -- more area, more flow.  so W/(m^2 \degree C) ?
   * But, flow is not just watts.  Must consider distance through the material.
   * Pushing 10W across 1m vs 10W 10m.  A watt-meter is the measure.
      * 10W through 1m; 20W through .5m; 5W through 2m, all the same.
      * So, $\frac{W m}{m^2 \degree C}$
      * Often shortened to $\frac{W}{m \degree C}$ but we'll stick with former.
   * Values: copper 401; silver 429; rock 5; snow ~.1; styrofoam .033;
   * You: 100W resting, 300 W exercising
   * Make a room 2m x 2m x 2m.  Each wall 4m^2, total 24 m^2.
   * Outside is -40C.  Keep inside 20C.  Use 100W
   * 4 W/m^2
   * So, a square meter, a meter thick, across 60C...
      * Rock: 5*60 = 300Wm.  75m for 4W
      * snow .1*60 = 6Wm.  1.5M of snow!
      * styrofoam .033*60 = 2Wm. 50cm of styrofoam
   * This is a pattern.  electrical conductivity, heat, diffusion, etc.
   * Try conductivity: $\frac{A m}{m^2 V}$
     * Watts J/s -> Amps C/s
     * $\degree C$ -> V

* Light energy
  * Speed of light.  3x10^8m/s
     * To oppose side of Earth .3s
     * Moon and back 3s
     * Sun to earh? 500s
     * Nearest star 150 millions (4.3 yrs)
  * Waves of elecricity and magnetism interleaved 90 degrees.
  * Frequency.  (Hz unit)
    * Any is possible
    * ULF radio 1000Hz or 1kHz
       * Wavelength?  (3x10^5 or 300,000m or 300km)
    * "normal" radio
    * IR
    * visible light (red)
    * visible light (green)
    * visible light (blue)
    * UV
    * Xrays
    * Gamma rays 10^20Hz
       * 8x10^-9, 8 nanometers.  100 atoms wide.
  * Concept of logarithmic scale
    * Example of size in m, from -3 to 3.
       * Place the earth on this?, the distance to the moon?, to the sun?
  * Analogy with sound
    * "octave" is 2x frequency.
       * 65 Hz "low C"
       * 130 Hz "Viola C"
       * 260 Hz "middle C
    * 10^3 Hz to 10^20 Hz is around 57 octaves or doublings
  * Visible light in more detail
    * Human color sense
    * Examples of colors, incl yellow
    * MS Paint
    * CMYK vs RGB
    * Limits on our vision
       * Different shade-resolution in e.g. green vs blue
       * Like having ears detecting only three pitches
       * What if we could see more colors (like shrimp)
  * "Blackbody radiation"
    * Different ways to transfer head: conduction, convection, radiation
    * Why ground can get colder than air at night
    * Why 22C can feel cold in a house with cold walls
    * Radiation rule $W/m^2 = \epsilon 5.67x10^{-8}T^4
    * Try our body heat: \epsilon = .95, T = 305K$ **466W/m^2, 816W total. 
    * Background of 295K instead? *Incoming is 714W, difference about 100W*
    * Body area say 1.75m^2.  
  * Cosmic background of about 2.73K, leftover from big bang.  Watts/m^2? **3.15x10^-6 W/m^2**
    * 1964, background noise in radio astronomy...And
  * Ground radiating at night
    * Model dry night sky as 225K ish  High emissivity
    * Compute difference with 290K ground, should arrive at 240 ish W/m^2
  * Greenhouse effect
    * CO2 passes UV but absorbs and reflects back IR
    * Serious greenhouse gas is *water*, however.  Humid night sky is more like 270K.
  * Quanta
    * Light waves and particles.  Hard to visualize; think packets of waves.
    * Energy from light comes in "quanta" of energy, with size related to frequency -- higher frequency, higher size.
    * eV unit $1.6x10^{-19}J$: one electron across a volt vs one coulomb across a volt.
    * $E = 1240\\lambda$ with E in eV and wavelength in nm.
    * Red light at ~700nm : 1240/700 = 1.77eV
    * Violet light at ~400nm: 1240/400 = 3.1eV
    * High gamma: 1x10^-6 nm, 1240/10^-6 = 1.24x10^9 eV (1.24 Gev)
    * Doesn't restrict W/m^2 -- just takes more or fewer quanta.
* Aside on relativistic light effects
  * Galilean relativity concept: motion is relative
  * Observing a wave in a medium lets you know if you're moving relative to the medium.
  * Sound, water waves, etc move through media.  Light was thought to move through an invisible "ether".
  * Michelson-Morley experiment showed there was no ether; light moves through space.
  * But... Does this mean we can observe a light beam and see if we're moving *relative to space itself*? No, for same reason there is no ether.
  * **A given beam of light appears to move at the same speed C even to two relatively-moving observers
  * Train experiment
     * Train moves at 50 m/s.  Standing on it you throw ball forward at 50 m/s
     * You observe ball moving relative to you; person on track sees it relative to them.
     * BUT, if it's a train moving at 1/2 C, and you shine a light foward, both see it as C!!!
     * How possible?  From track observer, *you* are moving slower and are compressed in dimension
     * He thinks you see the light as C because of this distortion.
   * Dimension and time themselves are relative!
   * Side effect we lack math for says E = MC^2.  
     * Joules in a kg of water: 1(3x10^8)^2 = 9x10^16J -- 80 megatons.
* Sound energy
  * compression waves in air
  * 343 m/s
  * https://onlinetonegenerator.com/
     * 60 Hz
     * 1000 Hz
     * Math for 1 Hz wave.  $sin(t)?  sin(\tau t)$
     * Math for 440 Hz: $sin(440\tau t)$
     * Discuss intuition behind $sin(\alpha) + sin(\beta) = 2 sin(\frac{\alpha + \beta}{2})cos(\frac{\alpha-\beta}{2})$
     * 440 Hz AND 441 Hz
     * Play interference pattern of 440 and various other tones
     * Concept of overtones.
   * Speed of sound in a gas:
     * Pressure wave is driven by speed of the molecules, roughly speaking.
     * Temperature is proportional to kinetic energy of the molecules, so...
     * Drops with air temperature, as *sqrt of K* since that's how speed changes with temperature.  So at 390K vs 360K (cold winter day) $\sqrt{360}{390}(343) = .96(343) = 330$
     * But speed at a given temperature is affect by mass of molecules,... how?
        * inverse sqrt of mass.  4x mass, 1/2 speed.
     * Helium molecules have .138 mass of air molecules.  So..
        * He speed is $sqrt{1/.138} = 2.7$ of air, and speed of sound in He is 924 m/s.  
        * Higher pitch of voice is because resonant waves in your sinuses move 2.7 times as fast and thus have 2.7 times frequency.
     * What about heavier molecules?
        * SF6 (5x air) demonstration: https://www.youtube.com/watch?v=u19QfJWI1oQ
        * See homework for more, and note bouyancy discussion to come and chemistry discussion to come.
     * Speed of sound in fluid or solid
        * Different factors, since molecules are in contact.
        * Based on density of the molecules, and forces between them.  * Imagine balls of different mass connected by springs of different stiffness. 
        * Very precisely understood, but more than this approximation requires advanced physics or physical chemistry.
        * Water: 1500 m/s.
   * Energy of sound
     * W/m^2 just like light, but very small.  Jet engine is 1 W/m^2
     * Ear can, theoretically, hear at $10^{-12}w/m^2$
     * Logarithmic scale, starting at 0 for $10^{-12}w/m^2$
        * Originally by 1's and named after AG Bell!
        * Refined to go by tens, thus "deci"bel, abbr dB
        * 50dB quiet office; 60dB conversation...
        * Show examples
        * Jet engine at 120dB is 1 W/m^2
        * Major rocket launch (e.g. starship booster) is 150 dB.  
           * Watts/m^2 is? <1000, like sunlight, but in physical form>
           * Need to scatter it with water spray to avoid damage (as Musk found out after first starship launch!)
     * Speaker power
        * "100 W" speaker is the input power.  1-5% efficiency to sound.  
        * Say 3W *output*.  How "loud" at perhaps 2m?
           * sphere area is $2\tau r^2$ (thus 12.56 "steradians")
           * $\tau r^2 = 6.28(4) \approx 25$ for half sphere
           * So, $3/25 = .12 W/m = -.921 bels or 19.21 decibels below the nominal 120 dB: 110.8 dB.  Still pretty loud!
        * Why so inefficient?  
           * "Impedance mismatch" concept, intuitively
           * Wave hand back and forth in air... in water..  Energy to move hand vs contributed to water...
           * Example of "horn" speaker, or just cupped hands
     * Sonic boom concepts
        * Wake of boat
        * pressure wave develops when moving faster than the wave speed.
        * Sonic boom is *constant* -- draw picture
        * Mach number is relative to speed of sound *in the context*
 * Nuclear/atomic energy
   * Periodic table and atomic structure (handout)
      * Nucleus of protons and neutrons, in balance, with neutrons on average slightly more.  Strong force holds together
      * "Orbiting" electrons.  (Recall definition of 1 coulomb)
   * Neutron/proton balance and atomic weight in atomic units
   * Why is atomic weight not an integer? 
      * Isotopes.  Carbon as example. C12, C13, C14
      * Hydrogen as another: H, H2 D, H3 T
      * Some are stable; some are not (C14, H3)
   * Radioactive decay.  
      * C14 has "too many neutrons", so **beta emission** to N14, stable.
      * Uranium as another example, this time of **alpha emission**
         * U92/238 = .387 p/n; Th90/234 = .385 p/n... 
         * Decay chain picture
      * Concept of "half life"
   * Helium story
      * Almost all radioactive emitted
      * Bonds with nothing as noble gas
      * Works its way upward from internal planet, captured by impermeable rock.
      * Eventually leaves atmosphere, and possibly solar system
   * Fission energy
      * Certain elements are fissionable, notably U235 and Pu239
      * Fission process -- extra neutrons trigger more fissions, etc.
      * Smaller resultant atoms have lower energy
      * Massive energy released by the fission, and also because the split atoms are themselves often highly unstable (too many neutrons) and rapidly do beta emission.
      * Result is "witches brew" of isotopes of varying radioactivity
   * Nuclear fallout
      * Dangerous roughly corresponds to fast-decaying
      * 7/10 rule wrt fallout.
      * Certain elements: sr90 and Cs137 are slower emitters (roughly 30 yrs halflife) 
         * Beta emission not too dangerous in environment but dangerous if ingested into bone or cells
   * Fusion energy
     * Smaller atoms into larger
     * Also releases energy.  (Iron/nickel at the bottom, which is partly why they're common)
     * Example for fusion reactor: D-2 + T-3 → He-4 + n + 17.6 MeV
     * How sun works, though more complex buildup
     * How "hydrogen bomb" works also.
     * Original atoms at big bang almost all H (74%) or He (24%) plus some H2, Li, Be, B.
     * All others form by some form of fusion in stars or more energetic phenomena
        * Gold ring formed in collision of two neutron stars, most likely
   
   
   

      

           
   

  




   

   
	