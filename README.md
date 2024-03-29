# solinks
collection of so questions

## Canonical candidates for Cython:

trying to collect canonical Q&As for cython

  * Error message “Cannot convert 'double *' to Python object” in Cython:  https://stackoverflow.com/q/53763480/5769463
  * Error message "Cannot convert Python object to ..."  : https://stackoverflow.com/q/47005382/5769463
  * Error message "Cannot covert Python object to type <typename>" for c++-classes : https://stackoverflow.com/q/52262669/5769463
  * How to specify Python 3 source in Cython's setup.py? https://stackoverflow.com/a/53992016/5769463
  * What does language_level in setup.py for cython do? https://stackoverflow.com/q/54900723/5769463
  * Cython: understanding a typed memoryview with indirect_contignuous memory layout https://stackoverflow.com/a/53951543/5769463
  * Wrapping C++ code with function pointer (or other non-type template parameter) as template parameter in cython https://stackoverflow.com/a/53584657/5769463
  * How to test if Cython property/function is generator? https://stackoverflow.com/a/53425234/5769463
  * declaration of functions with `except`: https://stackoverflow.com/a/50687119/5769463
  * cdef's cannot be accessed from pure python: https://stackoverflow.com/q/30228821/5769463
  * don't use cdef float for timer.time(): https://stackoverflow.com/q/55997211/5769463
  * mixing cdef and normal attributes in a cdef class: https://stackoverflow.com/q/42632297/5769463
  * importing with another Python-version: https://stackoverflow.com/q/65597206/5769463
  * Creating a numpy datatype from Cython struct: https://stackoverflow.com/q/62448946/5769463
  * Speeding up Numpy with Cython: https://stackoverflow.com/q/70821944/5769463

#### pickling:

  * pickling of namedcollection with Cython: https://stackoverflow.com/a/55236951/5769463
  * pickling typed memory-view with Cython: https://stackoverflow.com/a/58343703/5769463
  * pickling cdef classes with \_\_cinit\_\_: https://stackoverflow.com/q/64069471/5769463
  
#### Building:

  * What is an undefined reference/unresolved external symbol error and how do I fix it?  https://stackoverflow.com/q/12573816/5769463

##### Python specific
 
  * different build-options for different cpp-files/ building c and c++ in the same project https://stackoverflow.com/a/59364990/5769463
  * building a static library in setup and then linking extensions against it https://stackoverflow.com/q/57673283/5769463
  * PYTHONHOME/PYTHONPATH for embeded interpreters https://stackoverflow.com/q/56857449/5769463
  * use third party so/dll in C- or Cython-extension: https://stackoverflow.com/q/63804883/5769463
  * right way to share C/CPP-code between extensions, ORD-violation example: https://stackoverflow.com/q/63875206/5769463
  
##### Windows specific
  
  * Using dll in C-extensions https://stackoverflow.com/q/63804883/5769463 (more Windows specific explanations, but less complete solution https://stackoverflow.com/q/62662816/5769463)
  * building extension for debug-build on Windows https://stackoverflow.com/a/59204487/5769463
  * static Python on Windows (don't do it...) https://stackoverflow.com/q/62492622/5769463
  * embeding Python into a dll with Cython https://stackoverflow.com/a/62417945/57694637
  * linking against library doesn't work, because library is 32bit: https://stackoverflow.com/q/63750020/5769463
  * cross compiling on Linux for Windows: https://stackoverflow.com/a/70474888/5769463
  * compiling using mingw-w64 : https://stackoverflow.com/a/70654723/5769463

##### Cython specific

  * creating a static executable https://stackoverflow.com/a/48836737/5769463
  * Make executable file from multiple pyx files using cython https://stackoverflow.com/a/52977319/5769463
  * Collapse multiple submodules to one Cython extension https://stackoverflow.com/a/52714500/5769463 https://stackoverflow.com/a/52729181/5769463
  * Link Cython-wrapped C functions against BLAS from NumPy https://stackoverflow.com/a/52925796/5769463
  * Using h/c-files created by Cython to embed Python in a C/C++-exe: https://stackoverflow.com/a/45424720/5769463
  * Taking care of multi-phase intialization in embeded Python (Cython>=0.29) https://stackoverflow.com/a/55669343/5769463
  * How to use shared-libraries in Cython-modules https://stackoverflow.com/a/45655654/5769463
  * Setuptools & using numpy without preinstallation https://stackoverflow.com/a/54138355/5769463
  * Cythons inlude_path vs. distutils include_dirs https://stackoverflow.com/q/56812008/5769463
  * how to cythonize `__init__.py` (also on Windows) https://stackoverflow.com/q/58797673/5769463
  * Warning LNK4197 on Windows  while building modules with cython https://stackoverflow.com/a/58866779/5769463
  * reloading Cython modules https://stackoverflow.com/a/55172547/5769463
  * how Cython and Numpy provide they functionality without need of link against them at link time: https://stackoverflow.com/a/58162089/576946344
  * changing built-in compile-flags: https://stackoverflow.com/a/57057959/5769463
  * numpy-header cannot be found: https://stackoverflow.com/q/2379898/5769463
  * pyx-file and cpp-file have the same name, clash of object files: https://stackoverflow.com/q/50719086/5769463
  
#### Numpy:

  * How to use user-defined types for numpy-array in Cython https://stackoverflow.com/a/50861680/5769463
  * How to initialize PyArray_API:  https://stackoverflow.com/a/47027598/5769463
  * How to pass ownership of pointer to numpy-array: https://stackoverflow.com/a/55959886/5769463
  
#### Performance:
  
  * Cython for SIMD-instructions: https://stackoverflow.com/q/49058949/5769463
  
#### OMP/parallelization:
   
  * accessing elements of a list in parallel: https://stackoverflow.com/a/60012137/5769463
  * using thread-local containers: https://stackoverflow.com/a/58813699/5769463
  * using different scheduling strategies: https://stackoverflow.com/a/58296988/5769463
  * more complicated OMP-things with Cython: https://stackoverflow.com/a/57967436/5769463
  * OMP-threads and Python-threads are different things: https://stackoverflow.com/a/53696844/5769463
  
#### Multiprocessing:

  * spawn and frozen scripts with multiprocessing: https://stackoverflow.com/a/47360452/5769463
  
#### Importing modules:

  * using different file-extension for modules: https://stackoverflow.com/a/59995134/5769463
  * order of importing so,py,pyc files: https://stackoverflow.com/a/56119980/5769463
  * reloading c-extensions: https://stackoverflow.com/a/55172547/5769463
  * How to use shared-libraries in Cython-modules https://stackoverflow.com/a/45655654/5769463
  * Collapse multiple submodules to one Cython extension https://stackoverflow.com/a/52714500/5769463 https://stackoverflow.com/a/52729181/5769463
  
#### Embeding

  * is there really no code in the resulting exe? https://stackoverflow.com/q/62388701/5769463
  * PYTHONHOME/PYTHONPATH for embeded interpreters https://stackoverflow.com/q/56857449/5769463
  * why option -Xlinker -export-dynamic is needed https://stackoverflow.com/a/67894308/5769463
  * embeding python as shared object on linux: https://stackoverflow.com/a/67894308/5769463
 
### Misc:
  
  * folding while converting to bytecode: https://stackoverflow.com/q/15171695/5769463, https://stackoverflow.com/q/34147515/5769463, https://stackoverflow.com/q/306313/5769463
  
## How-to

tutorials how to do something

  * How to test functions cdef'd in Cython https://stackoverflow.com/a/53696970/5769463
  * How to use user-defined types for numpy-array in Cython https://stackoverflow.com/a/50861680/5769463
  * How to create a C-Closure (also jit with Python) https://stackoverflow.com/q/51044122/5769463
  * Putting PyObject* into C++-data-structures: https://stackoverflow.com/q/53695695/5769463



## Question I'm returning to from time to time:

Q&As I found useful (for different reasons)

  * "Why does `PyObject_GenericSetAttr` behave differently with lambdas than named functions" - https://stackoverflow.com/a/51794949/5769463 - Links to using gdb for cpython-debugging
  * How interning works in CPython https://stackoverflow.com/a/53506425/5769463 also https://stackoverflow.com/a/55644780/5769463
  * using ffi with numba https://stackoverflow.com/a/52958324/5769463
  * example of profiling with python https://stackoverflow.com/a/52750168/5769463
  * using callgrind with python: https://stackoverflow.com/a/50732998/5769463



## my pathetic hall of fame

answers I'm proud of (obviously without objective reasons):

  * Differences between PyCFunctionObject and PyFunctionObject, decriptor protocol, LOAD_METHOD-ptcode: https://stackoverflow.com/a/51794949/5769463
  * Memory layout of unicode-objects, how pymalloc works: https://stackoverflow.com/a/54030412/5769463
  * Memory consumption of int-object, how pymalloc works: https://stackoverflow.com/a/55621875/5769463
  * Using pymalloc as allocator for c++-maps/performace tests: https://stackoverflow.com/a/56551790/5769463
  * Why so are loaded before py-files? https://stackoverflow.com/q/56004885/5769463
  * numexpr sets the number of vml-threads: https://stackoverflow.com/a/59603509/5769463
  

## git tricks

  * merge current branch (`dev`) into master: `git push $(git rev-parse --show-toplevel) dev:master`: https://stackoverflow.com/a/20788245/5769463
  * rebase only part of the branch: `git rebase —-onto <place-to-put-it> <last-change-that-should-NOT-move> <change to move>`: https://stackoverflow.com/a/34927492/5769463
  * tag a release via command line: `git tag -a v1.0.1 -m"my info about v1.0.1" &&  git push origin v1.0.1`
 : https://stackoverflow.com/a/48534947/5769463
                   
 
