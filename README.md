# tdms_matlab
Code written to read TDMS files with Matlab.

This code was originally written and posted on the Mathworks File Exchange. This is a copy of that code although eventually that download link may originate from here.

# Usage
See TDMS_Documentation.m for important info.
See private/TDMS_exampleFunctionCalls.m for examples

This folder and the "tdmsSubfunctions" subfolder need to be in the Matlab path.

Simplest Usage (I think):
```matlab
filename = '';
my_tdms_struct = TDMS_getStruct(filename);
```

# Design
This was my first attempt at writing a TDMS reader and one of the first file parsers that I wrote. I made some ok design decisions but I wish I had done a lot of things differently. I have started an object oriented version although I have so many other things I'd like to work on that improving on something that works is very low on my list.