# JuliaSNN

Julia ecosystem for Spiking Neural Network simulation and analysis.

The packages are being defined and may present some inconsisencies. 


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
