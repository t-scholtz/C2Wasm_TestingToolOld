# C2Wasm_TestingToolOld
Mutation testing tool for C to Wasm conversion

Zip files are identical, just different formats

To use you will need to download: Mull mutation testing tool - https://mull.readthedocs.io/en/0.17.0/SupportedMutations.html Emscripten - https://github.com/emscripten-core/emscripten} Wabt - https://github.com/WebAssembly/wabt debugou.js - https://github.com/BeamNG/BeamNGpy

And it was designed to work with the C testsuite - https://github.com/c-testsuite/c-testsuite

You will also need to edit the files following files path. wasmfiles/conv.h Line 27 ,28 and 29 Line 44, 45 and 46 line 80 line 85 line 91 line 95 line 103 line 107 line 111 line 149-153

wasmfiles/findErrors.sh line 22, 24, 25 and 29 line 36 - 59 line 64 line 69

To Run: Add Test C code under testprograms/raw_programs In Wasmfiles/webApps run an instance of $ Python -m http.server in testprograms run $ bash ./ conv.py
