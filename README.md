THe research presentation is an informal collaboration update for my progress on modeling cosmic ray showers on the HAWC telescope. 

The arrival direction of cosmic rays should isotropic in azimuth, but this does not match observations. Why? The goal of this research was to 
explore possible explanations such as local mountains, detector geometry, cascading effects, and the earth's magnetic field.

Ultimately, the main suspect was the magnetic field. I wanted to generate airshowers on the array that had not experienced any magnetic field to see if the azimuth distribution changed.

- CORSIKA is used to simulate airshowers, specifically can set strength of earth's magnetic field
- HAWCSIM takes the simulated showers and throws them on the detector array, simulating how HAWC would observe the shower
- Offline Reconstructor (OR) takes observation data from HAWCSIM and attempts to 'reconstruct' the shower and determine parameters ie core location, energy, arrival angles
- Monte Carlo data is used for comparision and error propogation

