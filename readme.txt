Objective: Calc the thrust of the system.

% Variables
rho = 1.225; % kg/m^3
P0 = 60; % PSI
Pe = 0; % PSI
v0 = 0; % reservoir velocity
Ae = .003 % m
A = 0.007431 % m 
V = .00032738139 % Volume of tube (m)

% M dot
mdot = rho * vf * A

% Momentum eq
% intital momentum

p = m*(vf-v0)
m1*(vf - v0) = m2*(vf - v0)

% Thrust eq
F = mdot * Ve + (Pe + P0) * Ae
