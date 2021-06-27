The HPCVL Working Template (HWT) is a tool for high performance programming. It has been developed at HPCVL since 2002. The tool supports any combination of serial, OpenMP multithreaded, or MPI parallelized code, in FORTRAN 90, C and C++. There are three main functionalities: management of multiple versions, simple profiling, and relative debugging.

In many cases, it is necessary to keep multiple versions of code, such as serial and different types of parallel, for different platforms, or various purposes such as debugging or profiling. It is best to maintain these versions from a single original source code, which can be done by using preprocessor constructs. The HWT helps users to detect source code and generate an arbitrary number of versions.

The HWT can also be used to collect CPU timing data for any section of the code from multiple test runs and eventually arrange them in the form of simple timing tables together with the corresponding speedups.

Finally, users can insert calls to the HWT library, and generate identifiers to label data that are produced from the code for the purpose of debugging. The labels are stored together with the data in temporary files and later checked by the HWT debugger against reference data, for instance from a serial version of the code. The data to be compared may be private, shared, duplicated or distributed, and generated in any order. The comparison with the reference is done by the debugger without the need for user interference.


Two papers for this project are published: 

https://doi.org/10.1109/ICPPW.2004.1328024 (https://ieeexplore.ieee.org/document/1328024), 
about the basics idea and our method for the relative debugging in the HWT. 

https://doi.org/10.1109/HPCS.2005.55 (https://ieeexplore.ieee.org/document/1430061), 
about this specific HWT software. 



