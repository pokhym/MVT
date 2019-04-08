# MVT
Maude Verification Tool
# Goals
* Automate a way to turn C code into a system module
* Create a way in which we can check for invariants
* First goal is to support Nats and Ints

# Progress
Stack push pop has been implemented with a NatList.  Also for loop emulation has been done

# TODO
* Stack needs to push byte by byte so we need a method of pushing a full Nat
* Need to integrate the for loop into the full configuration and rename it
* while loops
* Verify small C program first by hand before going into automation

# Long term TODOs
* Figure out function calls
* C-lib functions such as strcpy
