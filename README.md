# Phonon Drag THz Emission Simulation

Numerical simulation of terahertz radiation generation from laser-excited metals via the phonon drag mechanism.

## Description

This Mathematica code solves the modified two-temperature model describing electron-phonon dynamics in metals under femtosecond laser irradiation. It computes:

- Time-domain THz waveforms `dEz/dt`
- Frequency spectra of the emitted THz radiation

The model accounts for finite phonon lifetime and momentum exchange between electrons and phonons, producing picosecond-scale THz pulses consistent with experimental observations.

## Requirements

- Wolfram Mathematica 12.0 or higher

## Parameters

The code is configured for gold (Au) with the following key parameters:
- Electron-phonon coupling: `G = 1×10^12 s^-1`
- Phonon damping rates: `α = 2, 3, 4×10^12 s^-1`
- Laser pulse duration: `τ = 200 fs`
- Simulation time: `t0 = 20 ps`

## Usage

1. Open the notebook in Mathematica
2. Evaluate all cells
3. The output displays two side-by-side plots:
   - Left: THz waveforms for three α values
   - Right: Corresponding frequency spectra

## Output

The code generates publication-ready figures with:
- Times font, thick frames
- Arbitrary units scaling
- Different line styles for each α value

## Author

Ivan Oladyshkin,  
Department of Nonlinear Electrodynamics  
A.V. Gaponov-Grekhov Institute of Applied Physics, RAS  
Nizhny Novgorod, Russia

## Acknowledgments

This work was supported by the Russian Science Foundation, grant #25-22-20019.
