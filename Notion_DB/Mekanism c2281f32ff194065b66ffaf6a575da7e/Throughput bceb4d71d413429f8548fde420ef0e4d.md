# Throughput

Universal Cable, Pressurized Tube, Mechanical Pipe have in their tooltip both a capacity and a pump rate. This page tries to explain how this comes together in computing the actual throughput of cables, pipes and tubes. While empirical trial and error usually works, understanding how to achieve a desired optimal throughput is critical in safely operating a fission reactor.

In Mekanism v10, Universal Cables have no Pump Rate indicated. Their actual pump rate is equal to the capacity of a single cable block:

- Basic: 8 kJ/t
- Advanced: 128 kJ/t
- Elite: 1.02 MJ/t
- Ultimate: 8.19 MJ/t

## Contents

- 1 Definitions
- 2 Pipe networks
- 3 Effective throughput
- 4 Pull mode
- 5 Examples

## Definitions

For convenience, we will use the following terms for the remainder of this page:

- Pipe: applies to any cable, pipe or tube
- Network: is a series of pipes of the same type connected together
- Acceptor: container or power consumer receiving power, fluids or gases from the network (energy cubes, machines drawing power/fluids/gases, tank valves, etc.)
- Emitter: any source of power, fluids or gases connected to and sending its contents to the network

## Pipe networks

When right clicking a pipe network with the Network Reader, we get this kind of output:

Empty pressurized tube network

- Transmitters: number of individual pipe blocks forming the network (this does not count any machine ejecting fluids/gases/power to the network)
- Acceptors: number of acceptors connected to the network
- Needed: this is just Capacity - Buffer (see below)
- Buffer: the contents of the pipe. This value can range from 0 (indicated as “none”) up to Capacity.
- Throughput: the amount of power/fluids/gases that transit through the network per tick.
- Capacity: The total power/fluid/gases capacity of the network. This is equal to the number of transmitters multiplied by the capacity of an individual pipe block

Note that a 0 value for the buffer means that the acceptors on the network drain it faster than the emitters send.

Another example that shows a non-empty buffer and actual throughput:

mechanical pipe network

## Effective throughput

Pressurized Tube tooltip The tooltip of a pipe shows:

- Capacity: the capacity contributed to the network by that individual pipe block
- Pump rate: how fast the pipe can accept/pull when set on “pull” with a Configurator

Each tick (1/20s):

- a pipe network tries to eject its entire buffer **evenly** among all acceptors
- a pipe network accepts up to its maximum capacity from emitters as fast as they try to send if they are auto ejecting via pipes set on normal (not pull)

Supposing that all tubes in a network are set to normal (the default), the theoretical maximum throughput of the network is the minimum of:

- the network total capacity
- the sum of the connected emitters send rates
- the sum of the connected acceptors receive rate

## Pull mode

When connecting a pipe to an emitter in pull mode:

- If the emitter auto-ejects to the pipe network, the effective throughput will be the sum of the emitter’s ejection rate and the pipe’s pump rate.
- For emitters with auto-eject turned off or which require a pipe in pull mode, the effective throughput will be the pipe’s pump rate. In order to increase the throughput from the same emitter, add more pipes in pull mode connecting the emitter to the pipe network.

## Examples

Some multiblock structures like Industrial Turbines, Thermoelectric Boilers and Fission Reactors have no actual send or receive rates. When piping them together, the only thing that really matters if the pipe network capacity vs. the heat rate of the reactor and boil rate of the boiler. Setting the pipes to pull mode would have no effect.

An Ultimate Energy Cube has a maximum output of 256 kJ/t. When connected normally to a cable network, regardless of the network capacity, the cube would only provide 256 kJ/t per tick, limiting the network throughput to that value (assuming there are no other emitters). However, if using an Elite Universal Cable in pull mode to draw power from it, one could achieve 1.28 MJ/t (256 kJ/t + the cable’s pull rate 1.02 MJ/t). This can be used to throttle the power consumption of a Supercritical Phase Shifter for example.