# Bayesian-C4-photosynthesis
Code for simulating C4 biochemical photosynthesis and deriving posterior distributions of Vcmax, Vpmax, ε, Jmax and Rd using Bayesian fitting of individual paired A/Ci-A/I response curves. The code is developed based on Wu et al., 2024.

Author information:
- Xia Jin
- xia.jin@uq.edu.au

Running environment:
- Python == 3.10.13;
- matplotlib == 3.8.0;
- pandas == 2.2.1;
- numpy == 1.25.2;
- pymc == 5.6.1;
- arviz == 0.16.0;
- pytensor == 2.12.3;
- Note: the code has been tested on macOS only (using a Macbook Pro M1 16GB RAM), and may not be compatible with Windows.

Reference
Wu, A., Truong, S.H., McCormick, R., van Oosterom, E.J., Messina, C.D., Cooper, M. and Hammer, G.L. (2024), Contrasting leaf-scale photosynthetic low-light response and its temperature dependency are key to differences in crop-scale radiation use efficiency. New Phytol, 241: 2435-2447. https://doi.org/10.1111/nph.19537
