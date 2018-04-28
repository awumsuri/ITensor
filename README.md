Homepage: http://itensor.org/

An efficient and flexible C++ library for performing tensor network calculations.

The foundation of the library is the Intelligent Tensor or ITensor. 
Contracting ITensors is no harder than multiplying scalars: matching indices 
automatically find each other and contract. This makes it easy to transcribe 
tensor network diagrams into correct, efficient code.

Installation instructions can be found in the INSTALL file.

## Emscripten Installation
Install Emscripten following these instructions
`https://kripken.github.io/emscripten-site/docs/getting_started/downloads.html`

Add `EMSCRIPTEN` home path to  `Path` environment variable

## Make Javascrpit file
Make itensor lib as normal. Build tutorials by running `emmake make` to create javascript file (Only for tutorial 01 currently)
