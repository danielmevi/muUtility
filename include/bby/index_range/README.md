# Introduction

This is a helper

 * This header provides a type safe implementation to manipulate a byte buffer
 * into an specific type descriptor.
 * The implementation it is meant to deprecate the use of reinterpret_cast from
 * a buffer into a struct pointer casting without performance and resource
 * penalties

# Usages

# Performance
## clang
## gcc

# Limitations

# Usage

# Examples

# Test
## Install conan
```
mkdir build
cd build
conan install .. -s compiler.libcxx=libstdc++11
```

## Generate Makefiles
```
cmake ..
```

## Compile
```
cmake --build .
```

## Run test
```
./bin/buffercast
```
