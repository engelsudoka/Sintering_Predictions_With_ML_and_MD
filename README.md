# Sintering_Predictions_With_ML_and_MD
Sintering_Prediction_With_ML_and_MD CNN and PINN models were employed to predicted Neck radius and ratio, Shrinkage, Density and MSD in MD simulation sintered Cu-Cu nanoparticles of various symmetric and asymmetric size pairs and temperatures for 200 ps 

This project develops machine learning models to predict sintering dynamics of copper nanoparticles, focusing on neck growth, shrinkage ratio, densification, and diffusion behaviour. Using trajectory data from LAMMPS molecular dynamics simulations across 36 sintering scenarios with varying particle sizes (3-12a₀), size ratios (1:1 to 4:1), and temperatures (300-900K), we engineered a comprehensive dataset capturing sintering metrics at each timestep. We implemented CNN and PINN to model the time-dependent sintering processes and compared predictions with molecular dynamics results and classical sintering models (Frenkel, Kuczynski, Scherer). Our ML models achieved mean absolute errors of 0.018 for neck ratio prediction and 0.022 for shrinkage ratio, outperforming classical models particularly in early sintering stages and asymmetric particle configurations. The study demonstrates machine learning's capability to capture complex sintering kinetics while providing computational efficiency advantages over traditional simulation methods.
# Sintering Simulation video



https://github.com/user-attachments/assets/76407e22-848c-41fc-ad41-bda0cdef0d67

https://github.com/user-attachments/assets/c0519186-463f-4473-b291-6556bded2049

# FEATURES FROM MD

<img width="1517" height="842" alt="fig3_time_evolution" src="https://github.com/user-attachments/assets/2cdd5eff-fbb3-47c9-8c46-d8a56d618ed8" />

# SCATTER PLOTs

<img width="2220" height="1328" alt="fig6_scatter" src="https://github.com/user-attachments/assets/e1c6fb35-22db-457d-89e5-3403a1c10984" />

# PARITY PLOTs

<img width="2984" height="1182" alt="fig8_parity" src="https://github.com/user-attachments/assets/4da55fbd-4ee0-48e9-925e-2f1260584ff2" />


# TIME SERIES PLOTS

<img width="2686" height="593" alt="fig12_time_series_good2use" src="https://github.com/user-attachments/assets/388b1e61-c131-467e-8772-41ade25cd3b6" />

