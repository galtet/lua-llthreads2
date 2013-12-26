lua-llthreads2
==============

This is full dropin replacement for [llthreads](https://github.com/Neopallium/lua-llthreads) library.

##Incompatibility list with origin llthreads library
* does not support ffi interface (use Lua C API for LuaJIT)
* returns nil instead of false on error
* start method returns self instead of true on success
* does not open all standart libraries (set LLTHREAD_REGISTER_STD_LIBRARY to on this feature)
* register loaders for llthreads library itself
