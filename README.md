# ABC-flow
fluid to solid one way coupling simulation

I used paris fluid solver (in Fortran) to solve navier stokes equation for Arnold-Beltrami-Childress flow, along with Volume of Flow method to update states. In this study case, a ellipsoidal drop with high viscosity and certain boundary conditions is treated as a solid. This program solves the multi-phase fluid problem.

As a result, it is found that drop with different orientation in ABC flow would result in different trajectory.

![alt tag](https://cloud.githubusercontent.com/assets/8973982/18479571/7e9eb67c-79a3-11e6-80a6-24d3b80b67fc.gif)

![alt tag](https://cloud.githubusercontent.com/assets/8973982/18479573/7fc2e744-79a3-11e6-8a86-a3b305ab0cbf.gif)

![alt tag](https://cloud.githubusercontent.com/assets/8973982/18479574/80ed85c0-79a3-11e6-8765-9f87c5cbe0c2.gif)
