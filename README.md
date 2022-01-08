# Responsive Motion Transition for Interactive Control of Walking Motion
We propose a set of walking motion data as input to be processed through a dynamic transitive method to produce the output as a smooth transition continuous
walking motion.

## Introduction
Dynamic transition for walking motion is a technique
of controlling the animation of walking motion.
One example of application in dynamic motion
is directing the character towards the destination
based on the user ’s control. However, a problem occurs
when performing the walking motions, especially
when making sudden changes by the user. It may involve
unbalanced poses and foot slides.
The purpose of this research is to generate continuous
walking motion based on the user ’s input
and maintain a balance of these motions. We propose
a set of walking motion data as input to be processed
through a dynamic transitive method to produce
the output as a smooth transition continuous
walking motion.
The idea of dynamic transition for walking motion
performed by some approaches, we determine
the timing when a sudden change is requested by the
user, trajectories for maintaining the balance, and
also posture correction to correct position of the posture
while maintaining the balance. 
We determine the timing to perform correct
transition time and to solve foot constraints by
defining the key times of the motion to match both
foot movements while perform the blending phase.



<p align="center">
  <img width="550" height="200" src="https://user-images.githubusercontent.com/22293987/136187169-24678516-4317-4690-839c-ddd4084b08cc.jpg">
  </p>
  <p align="center">
   Fig 1: example of transition of the motion
  </p>
  
  ## Dynamic transition for walking motion
The idea of dynamic transition for walking motion
performed by modifying each pose during the transition
to prevent unbalance pose and the foot sliding
problem. We determine the timing to perform correct
transition time and to solve foot constraints by
defining the key times of the motion to match both
foot movements while perform the blending phase.
We represent a timeline as an argument to display
information on motion when performs determine the
timing method. If the condition of the foot moving
together between motions, we determine the timing
and blending phase of the foot of both motions. However,
if the walking of the foot shows differently then
we determine the landing time of the moving foot.

<p align="center">
  <img width="650" height="100" src="https://user-images.githubusercontent.com/22293987/148620916-a6cb94e0-b158-40bc-ab05-ecb2f4079d22.png">
  </p>
  <p align="center">
   Fig 2: example of timeline illustration for determine the timing
  </p>
