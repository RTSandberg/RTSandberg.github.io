---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
---
I am a computational plasma physicist at the University of Michigan finishing a PhD in Applied and Interdiscplinary Mathematics and Scientific Computing.  When not working, I'm spending time with my wife and children.  We enjoy reading, gymnastics, eating, and pickleball, not necessarily in that order.

Research interests
---
I like my work in plasma physics.  I get to be part of the universal subject -- in addition to comprising 99% of the observable baryonic universe, plasma physics has many exciting applications and sits at several frontiers of fundamental science.  These include compact accelerators and radiation sources, high-field physics, high energy density science, extreme astrophysics, laboratory astrophysics, fusion energy, hall thrusters, and heliophysics.

My dissertation work consists of two projects: phase matched photon acceleration (PMPA) and the plasma code FARRSIGHT.

Phase matched photon acceleration is a scheme for frequency upshift using tapered plasma profiles.  This scheme uses an analytic nonlinear model for the wake behind an ultrarelativistic drive beam in the tapered density profile.  This leads to a coupled set of differential equations for the plasma profile and predicted laser pulse frequency.  Incorporating the derived profile in plasma simulation using the plasma codes OSIRIS and FBPIC, the laser pulse achieves 5-10x frequency shift in simulations.

The plasma code FARRSIGHT is an adaptive semi-Lagrangian particle method for an integral form of the Vlasov Poisson system.  FARRSIGHT employs a custom smoothly periodic regularization of the Green's function.  This is employed in a barycentric Lagrange interpolating treecode (BLTC) and deployed on GPU for more than 1000x speedup over direct sum CPU calculations for the problem sizes I've studied.  I developed an adaptive (modified) quadtree structure compatible with a hierarchy of interpolation schemes; the bilinear and biquadratic interpolation have actually been implemented.
