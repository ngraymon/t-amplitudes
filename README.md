Final adjustments to the repo are being made before it is ported over from gitlab.
With 3+ years of commits there are some remaining technical challenges.
For questions, information or a look at the current code please reach out to me at neil.raymond@uwaterloo.ca.


# t-amplitudes

Software for running the vibrational electronic coupled-cluster (VECC) approach as outlined in [10.1063/5.0190034](https://doi.org/10.1063/5.0190034).
The VECC method is aimed at simulating photo-electron/UV-VIS absorption spectra, as well as time-dependent properties for non-adiabatic vibronic models.
The repo also contain assorted scripts for generating spectra[^1] and managing vibronic models[^2].
The equations-of-motion (EOM) are generated using the package [termfactory](https://github.com/ngraymon/termfactory)

Additional branches will be added for calculating thermodynamic properties using the vibrational electronic-thermofield Ccoupled cluster (VE-TFCC) approach as outlined in the [10.1021/acs.jctc.4c00338](https://doi.org/10.1021/acs.jctc.4c00338)

Ongoing optimizatiton for larger models is ongoing, with recent work producing 2-3x improvments for larger models (A > 8, N > 5).

[^1]: using `autospec` from MCTDH
[^2]: using the `vIO` module, with a fairly recent version available [here](https://github.com/ngraymon/vmio). (Most of the module originated from [these scripts](https://github.com/ngraymon/Pibronic/tree/master/pibronic/vibronic)).
