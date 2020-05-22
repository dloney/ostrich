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

