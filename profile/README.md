# JuliaSNN

Julia ecosystem for Spiking Neural Network simulation and analysis.

The packages are being actively developed may present some inconsisencies. 

## SpikingNeuralNetwork.jl

Main package of the ecosystem, it defines: 

- the types necessary to all the packages;
- the routine for the simulation and recording of the models;
- the models implementated in `src/neurons` and `src/synapses`.

## SNNUtils

It contains various tools used to run complex simulations: 

- `src/IO`: tools to store and load simulations;
- `src/stimuli`: tools for complex simulation protocols;
- `src/analysis`: processing spike data;
- `src/models`: sets of parameters associated to publications (`<: AbstractParameter`).

## Examples

Collection of realistic simulation examples from published studies.

## SNNPlots

WIP

## SNNGeometry

WIP