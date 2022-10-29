# C-Wrapper-Library-Thing
### Still working on the name so it will change. I'm not sure when.

# Docs
## How this library works:
 ### When including this library in your own code, there are some things you should know before staring.



### When using this library, you must use to '#define' macro in C++.
### When defining what parts of the library you want to use, a list of the current APIs is provided as follows:

#USING_VECTOR
### Namespace to vector: 'mp::stlcppsl::containers::sorted' 
   ### or 'mp::stlcppsl::containers::sorted::mutex'
###Allows you to use a sorted, thread safe vector for managing arrays in contiguous memory.
##Usage:
   ### Just as if you used '#include <vector>'

#USING_IO
###Namespace to console: 'mp::stlcppsl::io'
###Allows you to use a more intuitive way of outputting to the console.
##Usage:
   ### 'console::log' outputs to stdout using 'std::cout'
   ### 'console::warning' outputs to stdout using 'std::clog'
   ### 'console::error' outputs to stderr using 'std::cerr'
