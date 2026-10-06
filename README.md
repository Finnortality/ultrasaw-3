# Ultrasaw (JUCE 8 VST3 synth)
Build: `cmake -B build -DCMAKE_BUILD_TYPE=Release && cmake --build build --config Release --target Ultrasaw_VST3`
Output: `build/Ultrasaw_artefacts/Release/VST3/Ultrasaw.vst3`
No local toolchain? Push this folder to GitHub; the included Actions workflow builds Windows + macOS VST3s as downloadable artifacts.
