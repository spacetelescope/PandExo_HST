# PandExo_HST
PandExo: A community tool for transiting exoplanet science with JWST & HST

Similar to an exposure time calculator (ETC), PandExo is a transiting exoplanet noise simulator. It is based on Pandeia, the ETC for JWST, and has been expanded to include HST's WFC3 instrument.

The included Jupyter Notebook tutorial demonstrates how to use PandExo to:

    1. Optimize WFC3's NSAMP and SAMP-SEQ parameters,
    2. Predict transmission/emission spectrum uncertainties, and
    3. Determine the observation start window
    
for any system observed with HST/WFC3 using the G102 & G141 grisms. The current implementation scales the measured WFC3 flux and variance from existing observations and has been shown to be reliable against previously-published results.

