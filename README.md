This repository showcases a common off-by-one error in C++ when iterating over a vector.  The `bug.cpp` file contains the erroneous code, leading to an out-of-bounds access. The corrected code is provided in `bugSolution.cpp`, demonstrating the proper way to iterate using `<` instead of `<=` to avoid accessing memory beyond the vector's bounds. This is a crucial aspect of C++ programming, highlighting the importance of careful loop condition management to prevent crashes or undefined behavior.