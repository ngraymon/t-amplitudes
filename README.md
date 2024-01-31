Final adjustments to the repo are being made before it is ported over from gitlab.
For questions or information about the code please reach out to me at neil.raymond@uwaterloo.ca.


# t-amplitudes

Software for running the vibrational electronic coupled-cluster (VECC) approach as outlined in JCP23-AR-04331R.
The VECC method is aimed at simulating photo-electron/UV-VIS absorption spectra, as well as time-dependent properties for non-adiabatic vibronic models.
The repo also contain assorted scripts for generating spectra[^1] and managing vibronic models[^2].
The equations-of-motion (EOM) are generated using the package [termfactory](https://github.com/ngraymon/termfactory)


[^1]: using `autospec` from MCTDH
[^2]: using the `vIO` module, which is largely dervied from [these scripts](https://github.com/ngraymon/Pibronic/tree/master/pibronic/vibronic)
