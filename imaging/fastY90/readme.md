## Description

This example demonstrates use of the fastY90 source.

## Set-up

The geometry consists in a world volume made of liquid water including one box (MainBox) made of liquid water.

## Physics

The Geant4 Standard option 3 physics list is assigned to the world volume and the MainBox volume with a cut of 10 kilometers 
to avoid secondary particles. A KillActor (allocated to the MainBox) is used to kill primary particles when they are created (before all interactions).


## Output

All spectrum sources are saved with an EnergySpectrumActor.
To analyse the spectrum with ROOT, use the plot.C macro file.
