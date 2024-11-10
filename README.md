This is an implementation of one-dimensional [LOWESS regression model](https://en.wikipedia.org/wiki/Local_regression) with a couple of examples of its applications to real data. The model was compiled from a C++17 source code into a shared library that can be used as a Python module (Linux). 

---
Usage Examples (Linux only)

* The [library](lib/lowess_model.so) that exports the Lowess model's interface from C++ to Python was compiled in Ubuntu 24.04.1 LTS with Python v3.12.3 + pybind11 v2.11.1.
* See [examples](examples) of how the model can be used.
* You can play with the model using a demo FastAPI app [here](https://lowessdemo.onrender.com/).
---
Documentation

[Doxygen documentation of the library](docs)
