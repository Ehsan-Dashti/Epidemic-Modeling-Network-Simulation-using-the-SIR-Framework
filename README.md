# Epidemic-Modeling-Network-Simulation-using-the-SIR-Framework
🦠 Epidemic Modeling & Network Simulation using the SIR Framework
This project applies network science and epidemiological modeling to simulate the spread of the 2009 H1N1 pandemic in Sweden. Using the SIR model on both synthetic and scale-free networks generated via preferential attachment, the simulations explore infection dynamics, the effect of vaccination strategies, and parameter tuning based on real-world data.

🔬 Core Concepts & Methods
🧪 SIR Model on Static Networks
Simulated disease spread over a 500-node graph with average degree k=6.

Infection and recovery rates: β = 0.25, ρ = 0.6.

Observed weekly counts of Susceptible, Infected, and Recovered individuals over a 15-week period.

Averaged results over 100 iterations to ensure convergence.

🔗 Preferential Attachment Graph Generation
Constructed scale-free networks to reflect real-world social connection patterns.

Visualized graph structure and degree distribution.

Analyzed how highly connected nodes influence early-stage transmission.

💉 Vaccination Modeling
Introduced progressive weekly vaccination following a realistic schedule.

Vaccinated individuals were excluded from transmission dynamics.

Assessed reduction in infections and the shifting of epidemic peak under vaccination.

🇸🇪 Real-World Scenario: 2009 H1N1 in Sweden
Calibrated model using real pandemic data from Sweden.

Tuned parameters:

Average degree k = 9

Infection rate β = 0.1

Recovery rate ρ = 0.2

Measured model accuracy using Root Mean Square Error (RMSE) between simulation and official weekly infection reports.

Found best-fit RMSE of 6.16, reflecting a close match to observed data.

📊 Key Visuals and Results
Weekly dynamics of S, I, R, and vaccinated populations.

Impact of network topology and superspreaders.

Comparative plots: with vs. without vaccination.

Convergence of simulation results to observed pandemic trends.

🛠️ Tools & Libraries
Python 3, NumPy, NetworkX, Matplotlib

Stochastic simulation techniques & data fitting

📁 Files
main notebook.ipynb: Complete code implementation with simulation logic and plots.

report.pdf: Full project report documenting methods, results, and analysis.
