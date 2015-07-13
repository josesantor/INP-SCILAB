# INP-SCILAB

INP SCILAB is a SCILAB-based Algorithm which, every fifteen minutes, i) reads two .csv files containing customers energy consumption and generation, ii) computes the power losses and voltage drops in the grid, iii) performs short-term prediction of the consumption/production power based on 1-year historical data sets, uses this forecasting to compute future power losses and voltage drops, and iv) finally writes the results on output files.
(from loadData.csv) - Last load profile information
(from weatherData.csv) - Last weather forecast
(to powerLosses_VoltageDrops.csv) - PowerLosses/VoltageDrops data for each Line of the trial grid,
(to predictions.cvs) - Load Prediction data for each Meter of the trial grid.

Prediction codes use the Lib-SVM library, which can be easily installed in SCILAB using ATOMS.