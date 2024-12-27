# PWMgenerator
This is a simulink file which is used to generate PWM carrier, you could use this file change PWM carrier phase and frequency. If you need generate the triangle PWM carrier, just delete the "2*pi" part in "phase_shift = phase * T / (2 * pi);", After that, maybe you need to add some easy mathematical block to set the range of PWM carrier in [0,1], [-1,1], oe other.

This file creat in MATLAB 2020b environment.
