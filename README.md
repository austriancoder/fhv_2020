## pyopencl - Hands On

This instructions are tested on Ubunut 19.04.

#### Setup
Please run the `./setup.sh` to prepare your OpenCL development setup.
After this you should be able to test if pyopencl is happy with your setup by running
`python dev_info.py`.

```
$ python dev_info.py

Number of OpenCL platforms: 1

-------------------------
Platform: Portable Computing Language
Vendor: The pocl project
Version: OpenCL 1.2 pocl 1.2 None+Asserts, LLVM 6.0.1, SLEEF, DISTRO, POCL_DEBUG
Number of devices: 1
        -------------------------
                Name: pthread-Intel(R) Core(TM) i7-6700 CPU @ 3.40GHz
                Version: OpenCL C 1.2 pocl
                Max. Compute Units: 3
                Local Memory Size: 16384 KB
                Global Memory Size: 2596 MB
                Max Alloc Size: 1024 MB
                Max Work-group Total Size: 4096
                Max Work-group Dims:( 4096 4096 4096 )
        -------------------------

-------------------------
```
