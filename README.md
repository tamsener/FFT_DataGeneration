# FFT_DataGeneration
## Definition of the code
This code reads the OpenFOAM probe data of velocities and creates energy specturum graph via FFT transform of the energy density function. This can be used to visualise the Large Eddy Simulation (LES) energy density spectrum.
It can be used to plot energy density spectrum via Fast Fourier Transfrom (FFT) directly from the probe data. It reads how many probes are located in the calcualtions, and reads U and Umean field that are written by the OpenFoam. User should only provide the paths of those files, and code reads and analyses the rest.

## Future work
1)It is planned to plot each probe data instead of one certain plotting.
2)Current resultant velocity fields were obtained from very coarse calculations (with Keqn sgs model of LES), it is planned to provide finer results.
