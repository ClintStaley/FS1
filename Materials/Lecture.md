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
   * BTU and Therm (1000 BTU)
      * old school "kcal" -- 1lb of water 1 degree F
      * Still useful in e.g. gas bills
      * No longer used in Britain!
   * kilowatt-hour
      * 1000W for 1 hour
      * How many J?  (3.6 x 10^6)
   * kiloton
      * Nominally 1,000 tons of TNT
      * Formally, 4.2x10^12J
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
* Electrical energy
   * amp definition
      * Interesting history on amp def
   * Volt definition
   * Watt = V*A
   * 15A wall socket at 120V gives?
   * Solar energy is about 1kw/m^2.  But cells are maybe 20% efficient.
* Run a car off solar cells on roof?
   * How much power?
   * How long to accelerate 1MT to 10 m/s?
* Heat Energy
   * Already discussed joules <-> calories, but is temperature/kg-joule the same for all substances?  
   * *Specific heat* capacity: $J/kg \degreeC$
      * Water?  (4184)
      * other substances: Iron 460; rock 800; air 1000
   * *Thermal mass* $J/\degreeC$
      * Multiply in the mass to get a whole "object's" capacity.  
      * Thermal mass of a cubic meter of water... ?
   * *volu8metric heat capacity* $J/m^3\degreeC$
      * water, *per m^3*...
* Heat flow
   * Thermal conductivity $W/m\degreeC$
      * delve into the units
   * Thermal conductance $W/m^2\degreeC$
      * Assumes the width, e.g. for a wall.

   

   
	