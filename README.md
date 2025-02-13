# Gaussian Boson Sampling Simulation

This repository contains a Python implementation of a Gaussian Boson Sampling (GBS) simulation using the Strawberry Fields library. GBS is a quantum computational task that demonstrates quantum advantage by sampling from the output distribution of a linear optical network with squeezed states as input.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

Gaussian Boson Sampling is a variant of Boson Sampling that uses squeezed states as input to a linear optical network. This project simulates a GBS experiment using the Strawberry Fields library, which is a Python library for simulating continuous-variable quantum circuits.

The simulation involves:
- Preparing input squeezed states.
- Applying a linear interferometer defined by a unitary matrix.
- Calculating the probabilities of specific Fock states at the output.
- Comparing the results with theoretical predictions using the Hafnian.

## Results

The simulation calculates the probabilities of specific Fock states for a given input squeezed state and compares them with the theoretical values obtained using the Hafnian of the corresponding matrix. The results are printed to the console, showing the probabilities and the comparison between the simulated and theoretical values.

## Dependencies

Strawberry Fields: A Python library for simulating continuous-variable quantum circuits.

NumPy: A fundamental package for scientific computing with Python.

SciPy: A library for scientific and technical computing.

The Walrus: A library for computing hafnians, permanents, and torontonians.

## Installation

To run this project, you need to have Python installed along with the required libraries. You can install the dependencies using the following commands:

```bash
pip install strawberryfields --upgrade
pip install xanadu-cloud-client
pip install numpy
pip install scipy
pip install thewalrus
