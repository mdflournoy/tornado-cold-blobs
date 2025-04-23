Contains select r20.3 CM1 files used to create the simulations analyzed in Flournoy et al. (Sensitivity of simulated vortex development to near-surface temperature perturbations).

Control run files:
- namelist.input
- input_sounding
- toy.input

Forward-flank run files:
- forwardflank-namelist.input
- forwardflank-toy.input
- input_sounding (same as the control run)

The other 24 restart ensemble members were created using the same files as the forward-flank run, except "warm0xc" and "warm0yc" were changed in toy.input to reflect the unique location of the cold blob in each run. Each of these varied by 2000 m.
