Massive MIMO with Non-Ideal Arbitrary Arrays
==================

This is a code package is related to the follow scientific article:

Emil Björnson, Michail Matthaiou, Mérouane Debbah, "[Massive MIMO with Non-Ideal Arbitrary Arrays: Hardware Scaling Laws and Circuit-Aware Design](http://arxiv.org/pdf/1409.0875)," IEEE Transactions on Wireless Communications, vol. 14, no. 8, pp. 4353-4368, August 2015.

The package contains a simulation environment, based on Matlab, that reproduces all the numerical results and figures in the article. *We encourage you to also perform reproducible research!*


## Abstract of Article

Massive multiple-input multiple-output (MIMO) systems are cellular networks where the base stations (BSs) are equipped with unconventionally many antennas, deployed on co-located or distributed arrays. Huge spatial degrees-of-freedom are achieved by coherent processing over these massive arrays, which provide strong signal gains, resilience to imperfect channel knowledge, and low interference. This comes at the price of more infrastructure; the hardware cost and circuit power consumption scale linearly/affinely with the number of BS antennas N. Hence, the key to cost-efficient deployment of large arrays is low-cost antenna branches with low circuit power, in contrast to today's conventional expensive and power-hungry BS antenna branches. Such low-cost transceivers are prone to hardware imperfections, but it has been conjectured that the huge degrees-of-freedom would bring robustness to such imperfections. We prove this claim for a generalized uplink system with multiplicative phase-drifts, additive distortion noise, and noise amplification. Specifically, we derive closed-form expressions for the user rates and a scaling law that shows how fast the hardware imperfections can increase with N while maintaining high rates. The connection between this scaling law and the power consumption of different transceiver circuits is rigorously exemplified. This reveals that one can make the circuit power increase as sqrt(N), instead of linearly, by careful circuit-aware system design.


## Content of Code Package

The article contains 5 simulation figures, numbered from 4 to 8. These are generated by the Matlab scripts simulationFigure4and5and7and8.m and simulationFigure6.m. 

See each file for further documentation. 


## Acknowledgements

This research has received funding from the EU 7th Framework Programme under GA no ICT-619086 (MAMMOET). This research has been supported by ELLIIT, the International Postdoc Grant 2012-228 from the Swedish Research Council and the ERC Starting Grant 305123 MORE (Advanced Mathematical Tools for Complex Network Engineering).


## License and Referencing

This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.
