# HI-21 cm Cosmology: Light Cones and Coevolving Plots
Astronomers use the finite speed of light to look back in time, aiding our understanding of the universe's formation. The 21-cm HI line, a hyperfine transition line, offers insights into the early universe, penetrating dust clouds and revealing conditions from the Cosmic Dawn and Epoch of Reionization. The signal's detection poses challenges due to its faint nature, but upcoming telescopes like the Square Kilometer Array (SKA) promise to improve observations.
This project explores HI-21 cm cosmology using light cones and coevolving plots. The study involves simulating the 21-cm signal to understand the early universe's structure, focusing on two key epochs: Cosmic Dawn and Epoch of Reionization.

# Methodology
Tools
21cmFAST: Semi-numeric modeling tool for simulating the cosmological 21-cm signal. It generates 3D realizations of density, ionization, peculiar velocity, and spin temperature fields.

Process
Generate Light Cones: Using 21cmFAST, a light cone cube was created with a size of 500 cMpc, covering redshifts 7-12.
Cosmological and Astrophysical Parameters: Specific parameters were set for the simulation.
Plotting: Python, numpy, h5py, and matplotlib were used to visualize the data.

# Results
Brightness Temperature: Higher redshifts show more HI regions compared to void regions.
Light Cone Effect: Provides a comprehensive view of signal variations over redshift, useful for understanding overall evolution.
Coeval Plots: Offer detailed snapshots of signal variations at specific redshifts, showing local conditions effectively.

Authors
Meghna Biswal
Supervisors: Dr. Abhirup Datta & Dr. Aishrila Mazumder
