# SineGordon
Numerical solution of the Sine Gordon Equation, the special analytical solutions are presented, 
we solve for the "double pole soliton" solution, through the use of a hybrid scheme composed of 
Lax-Wendroff for the fiirst time step and the [Box-Scheme, Crank-Nicolson-Scheme] for the rest of the time steps, we utilized 
dirichlet boundary conditions, and a given initial condition. I and a partner experimented with the use of what 
we have defined to be "Hybrid Schemes", a problem arises when using two level schemes, in that we require two time levels to 
initialize the scheme, thus t = 0 and  t = 1, must be already generated. We solve the issue by generating t = 1 through the use of
the Lax-Wendroff Scheme which is not a two level scheme. I have posted this code for modification, please go a head and use it. If you
have any questions please let me know. These Hybrid Schemes are rather irratic, for some analytical solutions second order is achived for 
others first, and for others it is much to irratic for pectical use. Keep this in mind if you are going to use it. In practice i recommend 
you use some of the fourth order schemes available for use in matlab.

