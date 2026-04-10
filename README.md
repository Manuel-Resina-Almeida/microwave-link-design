This project was developed for the Telecommunications Systems Project course at ISCTE-IUL (2024/25). The main objective was to design from scratch a bidirectional digital microwave link to transmit an STM-1 signal (155 Mbit/s), supporting 64 video channels between two Digital Terrestrial Television (DTT) stations.

The project encompasses the entire lifecycle of a network engineering problem: from initial terrain profiling to hardware selection, ITU-R compliance validation, and a comprehensive 25-year financial analysis.

Technical Analysis & Link Budget
Terrain Profiling: Extracted elevation data (Google Maps API) to plot flat and spherical earth profiles, calculating the first Fresnel zone to justify repeater placements and avoid signal obstruction.

ITU-R Compliance: Conducted in-depth frequency band and modulation studies to meet strict ITU-R specifications.

Link Optimization: Calculated emission power, receiver noise factors, optimal frequency selection, and verified a 3 dB critical margin for the final optimized link.

Simulation: Utilized Feixer software to simulate the direct path and the final optimized relay path.

Financial & Feasibility Study
Engineering requires cost-effective solutions. This project includes a CAPEX/OPEX minimization study over a 25-year lifecycle:

Factored in equipment costs (antennas, waveguides, masts, shelters).

Calculated licensing fees, annual exploitation charges (30% of initial cost), and terrain rights (40%).

Modeled an Internal Rate of Return (IRR) of 25% and an inflation rate of 2.3% to calculate the average daily utilization cost per video channel.

Repository Structure
/Report: Contains the final 20-page technical report detailing the complete network architecture, mathematical justifications, and equipment listings.

/Frequency_Studies: Spreadsheets and comparative tables analyzing different frequency bands and modulations.

/Feixer_Simulations: Simulation data for the direct and optimized network paths.
