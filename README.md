
# SimpleAllocator

A minimal custom C++ memory allocator that plugs into the STL and demonstrates how allocation, deallocation, construction, and destruction work under the hood.  

This project showcases **low-level memory management** in C++ by overriding the default allocator used in `std::vector`. It prints debug messages whenever memory operations are performed, giving insight into how the STL containers interact with allocators.

---

## Features
- Custom implementation of `allocate` and `deallocate` using `::operator new` and `::operator delete`.
- Debug messages to track memory operations.
- Integration with `std::vector` to demonstrate real usage.
- Example of overriding `construct` and `destroy` to manage object lifetimes.

---

## Example Output
When running the program, you’ll see how memory is allocated and freed as the vector grows and shrinks:

