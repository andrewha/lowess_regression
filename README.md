This is an implementation of a [LOWESS regression model](https://en.wikipedia.org/wiki/Local_regression) with a couple of examples of its applications to real data. The model was compiled from a C++17 source code into a shared library that can be used as a Python module. 

---
Usage Examples (Linux only)

* The [library](lib/lowess_filter.so) that exports the Lowess model interface from C++ to Python was compiled in Ubuntu 24.04.1 LTS with Python v3.12.3 + pybind11 v2.11.1
*  See [examples](examples) of how the model can be used.

---
Documentation

[Doxygen documentation of the library](docs/html)
