# turbogap-mpirun-issue
Files related to issues faced when running an identical process on 2 cores and 4 cores.<Br>
## Details
The MD being run is heating 2 defective fullerene molecules at 9000 K for 3 ps. The files `trajectory_2core.xyz` and `trajectory_4core.xyz` are the results of identical MD settings being run in a supercomputer with 2 cores and 4 cores respectively. However, as you can see, the results are drastically different, where for some reason `NaN` results are consistently produced when running the process on 4 cores.
