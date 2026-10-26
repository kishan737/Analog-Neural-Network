# MOSFET-Based Analog Neural Network

## Overview

This project explores analog neural network computation using MOSFET-based circuits. The design was inspired by a CMOS 180 nm research topology and uses transistor operating characteristics to implement weighted computation and nonlinear activation.

The network was designed and evaluated through SPICE simulation, with XOR classification demonstrated using a four-neuron architecture consisting of three hidden-layer neurons and one output neuron.

## Circuit Design

The analog neuron was developed using MOSFETs operating in the triode region as voltage-controlled resistive elements for implementing synaptic weights.

The circuit includes weighted-sum computation, level shifting, gain stages, and nonlinear output limiting to reproduce the basic behaviour of an analog neuron.

## Simulation and Analysis

SPICE simulations were used to examine the circuit blocks and evaluate transistor operating regions, input and output voltage ranges, output swing limitations, and non-ideal circuit behaviour.

The design was evaluated by combining the neuron circuits into a small network capable of classifying the XOR logic function.

## Network Architecture

The network consists of four analog neurons:

- Three neurons in the hidden layer.
- One neuron in the output layer.

The network uses analog circuit behaviour to perform the weighted computation required for XOR classification.

## Technologies and Concepts

MOSFET circuit design, analog computing, CMOS circuits, triode-region operation, voltage-controlled resistive synapses, SPICE simulation, nonlinear activation, neural network architecture, XOR classification.

## Achievement

Winner at Genesis 2.0.

## Future Improvements

Potential extensions include evaluating power consumption, analysing sensitivity to transistor parameters, testing robustness to noise and process variations, and comparing simulated circuit behaviour with a physically fabricated implementation.
