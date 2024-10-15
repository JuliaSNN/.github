# JuliaSNN

Julia ecosystem for Spiking Neural Network simulation and analysis.

## Usage

The packages are not available in the Julia's repository yet, for the moment you have to download the modules separatedly.
We suggest to:

`git clone https://github.com/JuliaSNN/SNNExamples`

``` julia
] add https://github.com/JuliaSNN/SpikingNeuralNetworks
] add https://github.com/JuliaSNN/SNNUtils

using SpikingNeuralNetworks
using SNNUtils
```


## Ecosystem structure

### SpikingNeuralNetwork.jl

Main package of the ecosystem, it defines: 

- the types necessary to all the packages;
- the routine for simulating and recording the models;
- the models implementated in `src/neurons` and `src/synapses`.

### SNNUtils

It contains tools used to run complex simulations: 

- `src/IO`: tools to store and load simulations;
- `src/stimuli`: simulation protocols and projections;
- `src/models`: parameters associated to publications (`<: AbstractParameter`).
- `src/analysis`: spike processing;

### SNNExamples

Collection of realistic simulation examples from published studies.


## WIP

### SNNPlots

Package with recipes for visualization, preferably in Makie 

### SNNGeometry

Package to generate Connections and Populations from geometrical parameters (density, layers, size... etc...)
