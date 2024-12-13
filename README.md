# DensityANDPolarizationINWater
The "density_polarization_water" code allows:

1) Extracting the dipole vector of individual water molecules from a trajectory file in GROMACS format and calculating the total polarization vector at a given time instant.

2) Plotting the spatial distribution of molecular dipoles in Cartesian coordinates, including a specific analysis of their distribution along the direction parallel to the total polarization vector and in the plane orthogonal to it. The code analyzes also the spatial distribution of sub-cell dipoles, calculated as the sum of the molecular dipoles within each individual sub-cell.

3) Compute the dielectric constant, isothermal compressibility, fourth-order polarization distribution Binder cumulant, and average density with the associated error obtained from block averaging.

4) Compute the intermediate scattering function, C(k,t), in a user-selected range of wavevectors k, for the fluctuations of the polarization parallel and orthogonal to the time-series averaged total polarization vector, the  polarization magnitude, and the particle number density.

5) Compute, in the same user-selected range of wavevectors k, the non-local susceptibility of polarization fluctuations parallel and orthogonal to the time-series averaged total polarization vector, the static structure factor of particles number density with respect to their center of mass, the non-local dielectric function parallel and orthogonal to the wavevector k, and the static correlation function between polarization fluctuations parallel to the time-series averaged total polarization vector and particles number density fluctuations, or the square of the polarization fluctuations orthogonal to time-series averaged total polarization vector.

The code is specifically designed for the TIP4P/Ice water model and a simulation box containing 1000 molecules; however, it can be adapted for different systems if required.

This code allows obtaining the results discussed in M.G. Izzo, J. Russo, G. Pastore, The interplay between liquid–liquid and ferroelectric phase transitions in supercooled water, Proc. Natl. Acad. Sci. U.S.A. 121 (47) e2412456121, https://doi.org/10.1073/pnas.2412456121 (2024).
