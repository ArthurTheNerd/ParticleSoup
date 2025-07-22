# ParticleSoup
This repository is about a simulation called **Particle Life**.

Particle Life is a simulation which essentially simulates proto cells in a canvas using particles that atract or repulse eachother. Here is how it works.

### How it works
Particle Life functions by creating a canvas full of particles, essentially like a soup. These particles have procedurally generated settings, which affects other particles. 

These settings are forces interacting with them and others, atracting of repulsing.

For example:

**Red**: Attracts *blue* IF inside of radius R, until IS in radiusSmall

**Blue**: Repulses *red* IF inside of radius R, until IS in radiusSmall

The result would be the blue particle trying to escape from the red, while it is chasing the blue.


Just these simple rules will eventually create the complicated results we want. 

Note: The current simulation contains 6 types of particles.
