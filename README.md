# LQR-and-LQG-Controller-Design-for-a-Cart-with-Two-Pendulums
The matlab files are structured as :

1. **`Linear_State_and_Controllability.mlx`**: Derives the linearized $A$ and $B$ matrices and verifies controllability.
2. **`lqr_linearized_system.mlx`**: Implements LQR design for the linearized model to determine the optimal gain $K$.
3. **`lqr_nonlinear_system.mlx`**: Simulates the LQR controller applied to the original nonlinear system dynamics.
4. **`Observability.mlx`**: Tests output vectors ($C$ matrices) to determine full state observability.
5. **`Luenberger_linearized_system.mlx`**: Designs a state observer for the linearized system using pole placement.
6. **`Luenberger_nonlinear_system.mlx`**: Tests the Luenberger observer's performance against the nonlinear system.
7. **`lqg_linearized_system.mlx`**: Combines LQR and Kalman Filtering for optimal output feedback on the linearized model.
8. **`lqg_nonlinear_system.mlx`**: Implements the final LQG controller on the original nonlinear system.

##  How to Run the Code

* **MATLAB Installation**: Ensure you have MATLAB (R2021a or later recommended) installed on your system or use MATLAB online editor.
* **Clone or Download**: Clone this repository to your local machine or download the ZIP file and extract it.
* **Set Path**: Open MATLAB and navigate to the project folder using the **Current Folder** browser.
* Each file is a **MATLAB Live Script** (`.mlx`), which allows to run code sections individually and view embedded results, equations, and plots.
