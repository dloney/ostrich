# OSTRICH
OSTRICH is a model-independent and multi-algorithm optimization and calibration tool. It can be used for: 

1. weighted non-linear least-squares calibration of model parameters 
2. constrained optimization of a set of design variables according to a user-defined objective or cost function; 
3. for performing global sensitivity analysis using the VARS plugin. 

Both single and multi-objective optimization are supported along with multi-criteria calibration. Parameters to be calibrated, 
optimized or analyzed can be log-transformed or computed as functions of other parameters. OSTRICH is also capable of computing 
an extensive set of post-calibration statistics, include confidence intervals, parameter correlation, tests of normality and 
non-linearity, and measures of observation influence and parameter sensitivity. 

OSTRICH can be configured to operate with any modeling program that utilizes text-based input and output file formats. 
Additional I/O formats that are supported include the MS Access database and netcdf formats. Executable versions of OSTRICH are 
available for both Windows and Linux-based computing environments. A parallel version of OSTRICH (OstrichMPI), utilizing the 
industry standard MPI interface, is also available in both Windows and Linux. Linux builds of OstrichMPI are available for both 
the OpenMPI and Intel-MPI implementations of the MPI standard. The Windows-based OstrichMPI uses the MS-MPI implementation of 
the MPI standard, which is distributed free of charge by Microsoft and can be downloaded from https://msdn.microsoft.com.

Instructions for building and using OSTRICH can be found on the OSTRICH wiki pages: https://github.com/usbr/ostrich/wiki.

## Acknowledgements
Funding for the creation of the user manual was provided by Environment Canada under contract number K3D35-14-0487R. 
Funding for the VARS (Variogram Analysis of Response Surfaces) implementation was provided by the Global Institute for Water 
Security at the University of Saskatchewan under the direction of Dr. Saman Razavi. The Dynamically Dimensioned Search (DDS) 
algorithm was developed by Professor Bryan Tolson and implemented in C/C++ code by Professor James Craig. Both James and 
Bryan are currently at the University of Waterloo. Professor Craig also provided routines for generating normally distributed 
random variables. Other variants of the DDS family of algorithms were ported to OSTRICH using C/C++ and FORTRAN implementations 
provided by Professor Tolson’s research group. Hyper volume calculations within the Pareto Archived DDS code have been adapted 
from original C++ source developed by Nicola Beume at the University of Dortmund. The Shuffled Complex Evolution (SCE) 
algorithm was ported from the original FORTRAN implementation of Dr. Qingyun Duan. All other algorithm implementations are 
based on published descriptions and were coded primarily by L. Shawn Matott. The basic object-oriented and model-independent 
structure of OSTRICH is based off of a code known as MACT (Multi-Algorithm Calibration Tool) that was developed by Vijaykumar 
Raghavan while at the University at Buffalo and under the supervision of Professor Alan J. Rabideau. Portions of the genetic 
algorithm and simulated annealing implementations in OSTRICH were ported from Mr. Raghavan’s MACT code.