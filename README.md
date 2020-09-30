# Logic Gates Simulation

*Coded 1600 Lines in 4 ½ hours.*

## Libraries Used :
- EaselJS for display and event models
- GSAP for menu animation

## Instructions
- Drag from an output connection (blue dot) to an input connection (grey dot) to create a wire.
- You may have multiple wires branch off an output, but only one wire per input.
- Click a connector (blue or grey dots) to remove all attached wires.
- Click (+) button in top-right corner to add new circuits.
- Note that some circuits are interactive


## Circuit Types

  INPUT / OUTPUT
- IN: A light with an input to turn it on.
- OUT: Interactive button with an output.

## LOGIC

- NOT: Outputs inverted input signal.
- OR: Output is true when any input is true.
- AND: Output is only true when both inputs are true.
- XOR: Output is only true when a single input is true.
- NOR: Output is true when neither input is true.
- MEM: One bit memory cell that can be switched on/off from inputs, and holds its state.
- TCK: A set frequency ticker that pulses a single tick signal every `n` ticks (configurable)
- DLY: Carries a signal after a delay of `n` ticks (configurable)


## Live Demo : https://Logic-Gates-Simulator.siddhantkcode.repl.co 