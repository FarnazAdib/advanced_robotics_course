# Advanced Robotics LQR Project

This repository contains code and resources for Linear Quadratic Regulator (LQR) control of linear, nonlinear, and time-varying systems, as part of coursework for CS287: Advanced Robotics at UC Berkeley.

## Project Structure

```
requirements.txt
try_lqr.ipynb
mats/
    cartpole_traj.mat
    heli_traj.mat
    p_a_w.mat
    p_b_w.mat
    p_c_heli_starting_states.mat
    p_c_w.mat
```

- **try_lqr.ipynb**: Main Jupyter notebook implementing LQR for linear, nonlinear, and time-varying systems, including helicopter and cartpole examples.
- **mats/**: MATLAB `.mat` files containing reference trajectories, starting states, and noise for simulation experiments.
- **requirements.txt**: Python dependencies required to run the notebooks.

## Getting Started

1. **Install dependencies**  
   Create a virtual environment (recommended) and install requirements:
   ```sh
   pip install -r requirements.txt
   ```

2. **Run the notebook**  
   Open `try_lqr.ipynb` in Jupyter Notebook or VS Code and run the cells in order.

## Features

- LQR for linear systems (infinite and finite horizon)
- LQR for nonlinear systems via linearization
- Linear Time-Varying (LTV) LQR
- Trajectory tracking for nonlinear helicopter dynamics
- Simulation and visualization of system responses under various controllers and noise

## Data

All necessary `.mat` files for experiments are included in the `mats/` directory.

## Acknowledgments

This code is adapted from CS287, Advanced Robotics, University of California at Berkeley, taught by Pieter Abbeel.

## License

For academic use only. See course policies for details.