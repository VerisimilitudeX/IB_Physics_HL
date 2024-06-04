# Stellar Fusion

- More massive stars have more fusion because they need to undergo more fusion in order to balance the higher gravitational force.
- More massive stars live longer because they undergo fusion more slowly.
- VERY massive stars become supernovae because the force of gravity overcomes the force of fusion when fusion ends.

## Nuclear Stuff 

- Critical point and chain reaction
- How to arrive at criticality without an explosion

# Radioactive Decay (6/3/2024)

| Decay Type | Particle | Example | Description |
|------------|----------|---------|-------------|
| Alpha decay | Alpha particles | Po-210 to Pb-206 | Releases energy. Can't go through things, doesn't hurt you because it's just helium. |
| Beta decay | High energy and speed E<sup>-</sup> (electron) or e<sup>+</sup> (positron) | Se-79 to Br-79<sup>-</sup> | Neutron turned into 1 proton and 1 electron and 1 neutrino. Adding 1 proton is not possible because it adds a positive charge, which is not allowed. Weak nuclear force allows up quark to change into a down quark, or vice versa. Will penetrate skin. |
| Gamma decay | High energy and speed gamma **rays** | Co-60 to Co-60<sup>*</sup> | Co-60<sup>*</sup> is an excited state of Co-60. Co-60<sup>*</sup> releases energy in the form of gamma rays. Will penetrate skin. |

## Measuring Radiation (6/4/2024)

### Background Radiation

- Background radiation is everywhere. It's not harmful because it's not concentrated. Examples:
  - Cosmic rays
  - Bananas
  - Watches with radium paint
  
### Measurements
- N: how much remains
- A: activity, how much is emitted
  - λN=-dN/dt
  - Exponential relationship between N and t
  - FORMULA: N=N<sub>0</sub>e<sup>-λt</sup>
    - t<sub>1/2</sub>=ln(2)/λ
    - Linearize by taking ln of both side
### Simulation

| Time (s) | N (amount that remains) |
|----------|---------------------|
| 0        | 100                 |
| 1        | 60                 |
| 1.5        | 45                  |
| 2        | 36                  |
| 3        | 23                  |

![N vs. t](Images/n.png)

We then linearize N to get useful data from it:

![ln(N) vs. t](Images/ln.png)

We can now calculate for the half-life of the substance:

t<sub>1/2</sub>=0.693/λ

t<sub>1/2</sub>=0.693/0.492 (we drop the negative because the equation already has negative)

t<sub>1/2</sub>=1.41 s