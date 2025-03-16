This project is about building drones. There is a lot of interest in drones these days, and a variety of industries have been impacted by improvements in drone technology and reductions in cost. If one simply wanted to have a drone, there are options on Amazon for under $50. However, that is not the purpose of this project. The purpose of this project is primarily pedagogical. I am undertaking this project as a means to teach myself how drones work. For the purposes of this project, I will try to minimize the amount of tutorial-style resources used. Of course, at some point, the limits of my existing knowledge will be reached and I will have to look to outside resources for help. To the extent possible, I will try to use outside resources that maximize learning.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Part 1: How does a drone work?

There are numerous scientific and engineering principles that drones take advantage of. Perhaps one of the most salient is that which answers the question: how does a drone (or anything for that matter) go from sitting on the ground motionless to hovering above the ground?

While it might seem pedantic or obvious to some, this is an important question that can form the basis for some interesting work on building a drone from scratch.

When we are talking about a drone lifting off, we can not avoid the physics that underlies this phenomenon. For an object resting on the ground to begin moving off the ground and into the air, a force must be applied to it. In the case of an object resting on the surface of the earth, as our drone presumably is, the force must exceed the force of gravity with which the earth pulls the object toward itself. We call the force of gravity pulling on an object the object's 'weight', usually measured in pounds (lb)  or newtons (N).

Newton's second law of motion, F = ma, dictates that for an object to accelerate (in this case, our drone going from a state of sitting stationary on the ground to moving upward into the air) it must be influenced by an unbalanced force. For our drone to move off the ground, it must somehow generate a force that exceeds its weight in the vertical direction. 

There are several ways the above can be accomplished. A common one is a rotor. A rotor is a type of wing that produces force by creating an air stream where low velocity air enters the steam and high velocity air exits it. To make an analogy, a rotor pushes against the air in the sense that a person would push against the ground to lift themself up.

The mechanics of how a rotor works are interesting, but they are not essential to making a drone that can fly. We can treat a rotor like a black box in the sense that, as long as it can produce more upforce than the weight of the drone produces downforce, it will suffice to lift our drone. For a given rotor, we really only have control over one thing: the rotational velocity, that is, how many RPMs it makes. This is where we can begin our practical exploration of building a drone. 

Our first experiment will be to obtain a motor with which we can induce some rotational motion, and a propeller that will convert that rotational motion into upforce. I think an interesting first exercise is to theoretically estimate the upforce produced by a given motor/propellor combination, and then to experimentally confirm or disprove our theoretical calculation.  
