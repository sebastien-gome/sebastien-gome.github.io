---
layout: single
title: "Research Overview"
permalink: /research/
---


My research focuses on statistical and geophysical fluid dynamics.

### 1. Self-organized turbulence {#self-organized}

When it is constrained by external forces like rotation, gravity or a magnetic field, a fluid often exhibits large-scale coherent motions which come to dominate its dynamics.
In idealized setups (like two-dimensional turbulence), this remarkable property can be traced to the presence of two quadratic sign-definite quantities, dynamically conserved at scales where energy injection and dissipation are too slow or absent. These two invariants constrain energy to accumulate at large scales (in an "inverse cascade" phenomenology). 
Classical three-dimensional fluids, however, do not obey such a constraint, as they conserve energy and helicity, the latter being sign-indefinite. This causes energy to flow to small scales.
But then, <span class="keyword">how come do some three-dimensional flows exhibit large-scale motions?</span>


In this research, I study how solid-body rotation comes to modify 3D flows and generate large-scale, effectively two-dimensional structures (aligned with the rotation axis).
We show that rotation spontaneously generates internal waves (called inertial waves), which, when interacting with large-scale two-dimensional modes, come to conserve an additional invariant: the wave helicity, but for each helicity sign. This additional, hidden invariant constrains the waves to generate and maintain large-scale 2D motions. This is an example of <span class="keyword">self-organization</span>: coherence spontaneously arises from fluctuating small-scale degrees of freedom (here the waves).
However, when rotation is sufficiently strong, 2D-waves interactions come to be depleted, due to a resonant effect. Therefore, in this limit, waves and 2D modes decouple: this is where a 3D-wave turbulent regime can be obtained, and where a purely 2D regime as well - depending on how the system is forced!
In the other direction, when lowering the rotation, there are less waves and some modes break the helicity constraint: these modes create a forward energy cascade, which coexists with the inverse. This type of scenario might actually be relevant in the ocean!

Refs:
- **S. Gomé & A. Frishman**, [*Helicity controls the direction of fluxes in rotating turbulence*](https://arxiv.org/pdf/2512.05253){:target="_blank"}.

- **S. Gomé & A. Frishman**, [*Waves drive large-scale 2D flows in rotating turbulence and cause their demise*](https://arxiv.org/abs/2509.18323){:target="_blank"}.



### 2.  Shear Flow turbulence {#shear}

There are two possibilites for turbulence to emerge in a flow: instabilities (like the shedding of vortices when wind comes to meet a mountain), or finite-amplitude kicks. 
Wall-bounded shear flows (like pipe, plane Couette or plane Poiseuille flow) are in the latter category, called a subcritical system. There, turbulence emerges by occupying an increasing proportion of space as the flow forcing (i.e the Reynolds number) is increased. 
This spatial propagation is dictated by the presence of localized, essentially discrete, large-scale turbulent structures, called puffs in pipe flow and bands in planar flows.
Transition to turbulence occurs via these structures either decaying or self-replicating. 
However, <span class="keyword">is this mechanism universal to all subcritical flows?</span>

In my PhD thesis, I showed how an emergent mean flow plays a crucial role in these systems by selecting the size of these discrete structures. This large-scale mean flow energizes turbulence from fresh incoming laminar flow, allowing it to stay statistically localized in space and create these individual structures. However, when this large-scale flow is suppressed, discrete structures disappear, and turbulence contaminates the flow via the propagation or retraction of small-scale vortices. This propagation scenario occurs via fluctuating turbulent fronts and also arises in curved or body-forced pipes. Surprisingly, while exhibiting a different propagation mechanism than in classical pipe or planar flows, these systems may still obey the same universal statistics. 
Indeed, in both cases, generic scaling laws of out-of-equilibrium phase transitions are expected if the fraction of turbulence evolves continuously with the Reynolds number.

### 3. Extreme events in turbulence

Turbulent flows can sometimes dratistically change configuration even if their fluctuations are relatively small. 
This type of events are particularly hard to predict with numerical simulations, as they rely the "high cost" of a configuration change from the internal chaotic dynamics in the flow.
Recently, new algorithms were designed to compute such rare dynamical events. They can be used to efficiently obtain transition probabilities, as well as relevant trajectories in phase space. 
Their use for fluid dynamics, like for computing when Jupiter's atmosphere will change, is very recent.

https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.122.074502
