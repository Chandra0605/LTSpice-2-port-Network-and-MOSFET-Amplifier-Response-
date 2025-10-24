# LTSpice-2-port-Network-and-MOSFET-Amplifier-Response-
This project involved the modeling, simulation, and analysis of advanced analog electronic circuits using LTSpice. The goal was to solidify understanding of theoretical concepts through practical simulation and to cross-verify hand-calculated and simulated results.
Two-Port Network Analysis
A complex two-port network consisting of resistors, capacitors, and a dependent voltage source was analyzed. The project objectives included:

Deriving Z, Y, and h (hybrid) parameters for the network at both low (1 kHz) and high (10 MHz) frequencies.

Validating hand calculations of these parameters by running AC and DC simulations in LTSpice and extracting network parameters using voltage and current probes.

Determining the optimal load at Port 2 for maximum power transfer when a 15V source is applied to Port 1, based on simulated and theoretical calculations.

Studying the sensitivity of output voltage (V2) to variation in the value of a key capacitor (C1), both analytically and using frequency sweep simulations.
This work provided practical insights into how frequency-dependent elements and controlled sources affect two-port network behavior.

MOSFET Amplifier Simulation
A common-source MOSFET amplifier with active load was constructed within LTSpice, using provided 500nm library models for realistic simulation. The main activities included:
•	Selecting appropriate biasing (V_bias) to ensure that both M1 and M2 MOSFETs operated in the active/ saturation region, as verified through DC operating point analysis.
•	Determining quiescent currents, node voltages, and verifying device operation points against manual calculations.
•	Plotting the frequency response of the amplifier by running AC sweep analysis and observing gain vs frequency.
•	Extracting and plotting the small-signal parameters (transconductance gmgm, body-effect gmbgmb, and output resistance roro) for each MOSFET, relating them to circuit performance.
•	Drawing and analyzing the small-signal equivalent circuit, comparing simulated and manual hand-analysis results.
This module reinforced the importance of iterative design and verification in analog circuit engineering, demonstrating how device parameters and bias points influence amplifier performance.
