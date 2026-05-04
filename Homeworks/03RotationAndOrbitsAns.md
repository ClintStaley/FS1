# Homework on Rotation and Orbits
In the following assignments:

  * Use $10 m/s^2$ for g, except when otherwise indicated
  * Show the work that arrives at your response. 
  * Use scientific notation for large and small values.  Learning to do this is one goal of the assignment.
  * When relevant, round answers to 3 digits.  
  * In all work, never use $\pi$.  Use $\tau$ instead.
  * In all work, express angles in radians.

### Basic

1. A modern jet engine turns at up to 10,000 RPM, with a radius of .45m.  What is the centripetal acceleration at the tips of the blades?  How much would a 1 gram of steel (a cube about the size of a pencil eraser) appear to weigh, in kg, at that acceleration?

**$V = 10000/60 * \tau * .45 = 471m/s;  \frac{471^2}{.45} = 492980 m/s^2$**

**49298 * 1gm = 49.3 kg**

2. Use the fact that earth orbits $1.5x10^8$ km (note km) from the sun to compute the acceleration toward the sun needed to keep the earth in its orbit.  Assume 365.25 days/year.  If we let the earth fall toward the sun for a minute at that acceleration, how far would it fall?  

**$V = 1.5x10^{11}*\tau/(365.25*24*3600) = 29,865 m/sec$**\
**$a = \frac{29865^2}{1.5x10^11} = .00595 m/s^2$**\
**$d = (.5).00595 60^2 = 10.7m$**

3. If the sun was the same mass as the earth, what would its gravitational attraction be at the distance of the earth?  Do this the easy way by figuring out how many earth radii 1.5x10^8km is (over 20,000 earth radii).  Then use that to reduce 9.8 by the right factor.  

    Compare that value with the acceleration it actually gives, from the prior problem, to estimate the sun's mass relative to the earth.  And use 9.8 for earth gravity in this one problem, to get a closer estimate.

**Radius ratio is $1.5x10^{11}/6.38*10^6 = 2.35x10^4$**\
**$9.8/(2.35x10^4)^2 = 1.77x10^{-8} m/s^2$**\
**$.00595/1.77x10^{-8} = 3.36x10^5 earth masses$**

### Bronze

4. A typical neutron star (a collapsed burned-out star, composed of packed neutrons) has a radius of 10km, and a mass 466,000 times that of Earth.  

   a. Starting with the value of g at Earth's surface, and using what we know of gravity, reason out the acceleration at the neutron star's surface.  Do this by multiplying and dividing g by the appropriate factors.  
   
   b. Then, based on your result figure what speed is needed to maintain an orbit around the surface of that neutron star.
   
   c. How does this compare with the speed of light: 3x10^8 m/s?

   d. How long would it take to go once around the star at that speed?  

**A mass of 466,000 times earth would mean an attraction of 4,660,000 m/s^2 *at Earth radius distance*.  But, the radius ratio is 6.3x10^6/1x10^4 or 630.  So, we multiply again by $630^2$ to arrive at 1.85x10^12.**

**Orbital speed is $\sqrt{1.85x10^12 * 1x10^4} = 1.36 x 10^8$**

**about 40% of light speed**

**Circumference is $10,000*\tau = 62,800m$, so orbit takes $62,800/1.36x18^8 = .000462s$**

### Silver
5. This scene https://www.youtube.com/watch?v=1wJQ5UrAsIY from the classic scifi film *2001 A Space Odyssey*, depicts an artificial gravity centrifuge on a deep-space ship.  The technology it depicts is certainly doable and might be used for space habitats.  But, especially at the size indicated, it has some interesting quirks.

    a. Assume device provides earth-normal gravity at the floor he runs on, and that it has a 6m radius.  How fast is it moving along the spin direction?

    b. Now, given your answer to a, and assuming the astronaut is 2m tall, what acceleration does he feel at his *head*, vs his feet, assuming he stands still.  This can be done with a very simple multiplicative factor on your answer to a.  Note that moving 2m toward the center changes both v and r in the $\frac{v^2}{r}$ equation.  

    c. What is the general rule for how the centripetal acceleration changes as r moves from 6m down to 0m?  For instance, given that halfway in, at 3m, both r and v are reduced by half, does that imply no change to the acceleration since the numerator and denominator are affected equally?

    d. Assume he runs at 2 m/s along the wheel.  Does it matter which way he runs (in the turning direction or opposed to it)?  What acceleration does he feel at his feet in each direction?

    e. Say he stands facing in the direction of the wheel turn, and quickly turns his head to the right 90 degrees to face the wall.  Estimate that his left ear briefly moves 1 m/s forward and his right ear moves 1 m/s backward, to make his head turn.  What acceleration (assume they're 2m above the floor) do his two ears experience for that brief instant?  Given that our ears provide the sense of "down", how do you think this feels to him?

**a.  $10 = \frac{v^2}{6}; 60 = v^2; v = 7.75 m/s$**\
**b. Hopefully here, and certainly for c, they see that the acceleration reduces proportionally with r since v and r both reduce, e.g. by 2/3 at his head, but in $\frac{v^2}{r}$ the squared effect on v means the acceleration also reduces by 2/3.  Whether by this argument, or just banging out the math, they should arrive at 6.67 m/s^2 at his head**\
**c. See b above.  They should reach this conclusion by some reasoning approximating what I indicate above.**\
**d. Makes a big difference.  Along wheel direction he gets $\frac{(7.75+2)^2}{6} = 15.8 m/s^2$. Opposite gets $\frac{(7.75-2)^2}{6} = 5.5 m/s^2$**
**e. Similar reasoning to d with v of 4.17/6.17 and r of 4 (ears are higher) means left ear gets 9.52 m/s^2 while right gets 4.35 m/s^2.  Accept reasonable answer on the "feel" but the best one is that his left ear feels like it's being accelerated up, and the right like it's being accelerated down, so he will feel like the floor is turning sharply downward to the right.  It will certainly affect his balance.**

6. Centripetal force equation $\frac{v^2}{r}$ is useful if we know the speed v.  But what if we only know instead the rate of rotation expressed in radians/sec.  This is called "angular velocity" and is often designated $\omega$.  For instance $\omega = 6.28$ means doing a full rotation every second.

    a. Derive an equation for centripetal acceleration that uses $\omega$ instead of v.  Your derivation should include a very simple relationship between $\omega$ and v.


    b. What $\omega$ is implied by a rate of 10 rpm (revolutions per minute -- commonly used to describe slow rotations)?  And, experiments show that sustained rotations of higher than 10 rpm make almost everyone nauseus.  Is the astronaut in that clip going to get nauseous?  


**a. Simple relation is that $v = \omega r$ by definition of radian.  Then $\frac{v^2}{r} = \frac{(\omega r)^2}{r} = \omega^2r$**

**b. $\omega = 10*\tau/60 = 1.047 R/S$  And this would mean $1.047^2(6) = 6.58 m/s^2$ so he's gotta be turning faster than that, and would be nauseous.**

### Gold

7. Assume a car at speed V makes a turn with radius R.  Given this information, what angle of embankment $\theta$ ($\theta = 0$ is flat, $\theta = \tau/4$ is fully vertical) of the road will prevent the car from sliding, even if the coefficient of static friction $\mu_s$ is 0 (e.g. on ice).   

    a. Using a free body diagram, come up with a simple equation for the normal force of the car on the road.
    
    b. Extend this work to arrive at an equation for bank-angle $\theta$ in terms of V, R, and g=10m/s^2.

    c. As a reality check, you should find that a car travelling at freeway speed of 30 m/s, going through a curve with 100m radius, requires an bank angle of .73R, a little under $45\degree$.  What would this same situation require for a bank-angle **on the moon**?

**a. FBD should show normal force F, with g component down and C component inward to circle.**\
**b.Then $F = g/cos(\theta)$ and $C = Fsin(\theta)$  But also $C = \frac{v^2}{r}$, so $\frac{sin(\theta)}{cos(\theta)} = \frac{v^2}{gr}$, and $\theta = tan^{-1}(\frac{v^2}{gr})$**\
**c. g is 1.6 instead, so $theta = \frac{30^2}{100(1.6)} = 1.39R$**











