# FileTrunc
ARCHIVED! See: https://github.com/melsbacksfriend/Melsbackslib

The first header in an awesome library called Melsbackslib

~~This will be archived when the second header is made.  Updates will continue in that repo.  ~~

This header takes a C string containing a file and path and returns a C++ string with just the folder name.  

This can be used with argv[0] to set the current working dir to the location of the file like in the example.  

# Building the example

git clone --recursive https://github.com/melsbacksfriend/FileTrunc.git

cd FileTrunc/FileTrunc-Example

g++ FileTrunc.cpp -std=c++17 -o FileTrunc

# Limitations

Doesn't work on Windows due to using backslashes.  
