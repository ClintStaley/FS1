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
 * Some examples of force situations
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
### Equal and Opposite forces
 * When two objects put force on eachother -- it's two way.  (push exercise)
 * Gravity is same -- two way
 * General principle: forces are *paired*
   * Newton's third law -- "Every action has an equal and opposite reaction"
   * In card lifting, forces are two-way
   * Raindrop pulls on Earth with opposite force, pushes back on air with opposite force
   * In our sign, add forces at each point.
		
	- Free Body Diagram worksheet - do some, leave the rest for homework.
	- Do an example with forces, like a train with couplings. Calculate the force in each coupling. Perhaps another with friction.
	- Ask what is actually happening with a force? Avoid gravity, and explain how tension, normal, applied force, etc (buoyancy if they mention it) are all at heart electrical repulsions. 
	- Now switch to gravity. What is actually happening here? Talk about the weight force and the mass. Use outer space (or the space station, though there is weight there) to distinguish between these. Explain that two asteroids would attract each other (like with invisible ropes or something connecting all the atoms?) and the force would be  Then segue to someone on earth - it's the M, you're the m. Have them calculate  and get 9.8. Explain how the weight force, on Earth, is thus mg. Discuss what happens other places, like the Moon.
	- Mention the importance of Newton tying orbital motion together with forces on Earth. Even the normal force isn't obvious to a lot of people the first time they take physics - they say something like the table cancels the gravity or something. 
	- Talk about free fall and why all objects fall, without air resistance, with a=g. Ask them whether two different balls will hit the table at the same time when they are dropped (they will, but a lot of them will say no). Use the equation to predict how long until a ball hits - have someone time it with their phone. It should work well. Mention Galileo and the Leaning Tower or Pisa (he demonstrated different objects all falling with g and, supposedly, people still didn't believe it). Ask, by the way, how they could prove a falling object is accelerating - just by sight, it's not obvious. They'll come up with ways, but ask, without a slow-motion camera? Galileo did it with sloped ramps and his pulse. Further, ask whether a can of lead shot or a can of feathers has different weights, different accelerations, or what?  
	- Now talk about falling with air resistance. Draw the FBD of a heavy object and a light object, showing how the air resistance is a higher percentage of the weight force for the light object. Talk about terminal velocity. Ask what this depends on. What if v is greater than terminal velocity (skydiver who pulls his parachute).
	- If time remains, discuss the friction force. Static (on-demand) and kinetic (always the same, in theory). How it varies with weight, because of the normal force. An example where the normal force is not the weight (holding something against the wall, for example - push harder if it slips).

Forces 2
	- Newton's 3rd law: if object A exerts a force on object B, then object B exerts an equal and opposite force on A. I start with "Push wars," a game where 2 ppl stand an arms' length apart with their hands held out, and try to make the other lose his balance. They'll notice that you can't push on someone if they don't push back. Talk about pushing on the wall, walking, swimming, a car moving, etc. N3 is a fundamental property of forces that always seems to hold.
	- The problem with N3 is when the forces are equal and opposite, but not an N3 pair, like gravity and normal for a book sitting on the table. Discuss this. The opposite to the normal is the book pushing on the table, and the opposite to gravity is the book pulling on the Earth. I like to say, "A on B, B on A" for an N3 pair. A more complex example is a cheerleader standing on another's shoulders, or something.
	- Application to a car accelerating, if you had time to mention friction before (if not do it now). Talk about how the car is moving. Calculate the max acceleration on a dry day, as opposed to a wet day. 
	- [If time] A more complex problem: block sliding down a ramp. Calculate acceleration.
	- Rotational motion and centripetal force. Ask them if a rotating object is accelerating. Does it have a constant velocity? So what's causing the acceleration? Well, it depends. Ask them for examples. Whirl a ball on a string, it's the tension. Car around a corner, friction. Planet, gravity.   
	- Show them that the centripetal acceleration has to equal v2/r for the object to move in a circle. I like using similar triangles on a small section of the motion (the angle between v0 and v1 is the same as the angle that the object moves through, in the limit, so by similar triangles, v*dt/r = dv/v and this dv/dt = v2/r). Talk about what happens if the acceleration is not exactly this. 
	- Example of a car going around a corner. As a group, calculate the max speed that a car can have on a corner of radius 200m or something.
	- Banked curves and how they help - the inward component of the normal adds to the friction force to create the centripetal force
	- Rope swing - some of them will have done this (if not, it's a great central Texas activity, they should try it) and know you have to hang on super hard at the bottom of the swing. Draw a FBD, talk about why. Calculate the force for a typical rope swing, or do this in HW.
	- Gravity and orbits. Solve for v as a function of r. Discuss geosynchronous orbits. 

Energy
	- Energy is an integral of a motion. Show how this works using 