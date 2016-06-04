# High Performance Lattices
Build Instructions:

1. Download and install llvm and Clang. Clang is assumed to reside in `/usr/bin/`.
2. Run `sh ./scripts/build_googletest.sh` to build Google Test.
3. Run `sh ./scripts/build_googlebenchmark.sh` to build Google Benchmark.
3. Download and install Intel TBB. For Mac OS X, run `brew install tbb`. For Ubuntu/Linux, run `apt-get install libtbb2`.

Run `sh ./scripts/build_debug.sh` to build the library in debug mode<br />
Run `sh ./scripts/build_release.sh` to build the library in release mode.

To run the tests, run `./build/tests/run_test`.<br />
To run the benchmarks, run `./build/benchmarks/run_benchmark`.
