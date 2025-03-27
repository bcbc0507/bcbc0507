## How to Use the MATLAB and Simulink Files for to simulate the motoring gear model

This README provides step-by-step instructions on how to use the provided MATLAB and Simulink files to understand and analyze the electric motor system. The research focuses on a motor with a stator, modulator, and permanent magnet rotor, and the files allow you to simulate its behavior, set input parameters, and analyze output data.

## Steps to Use the Files
---

## 1. Clone the Repository

Clone this repository to your local machine

## 2. Open MATLAB and Simulink

Launch MATLAB and navigate to the cloned repository folder.

## Files Included

1) **Motoring_Gear_param.m**:

This MATLAB script defines the parameters of the motor, such as pole pairs, pole pieces, speeds, torques, and other relevant variables.

Running this file saves the parameters into the MATLAB workspace, which are then used by the Simulink model.

2) **Motoring_Gear.slx**:

This Simulink file contains the block diagram implementation of the electric motor system.

It uses the parameters defined in **Motoring_Gear_param.m** to simulate the motor's behavior.

You can set input parameters (e.g., voltage) and read output data (e.g., rotor speeds).

## 3. Open and Run the MATLAB File (**Motoring_Gear_param.m**)

-Open MATLAB and navigate to the folder containing the files.
-Open and run the **Motoring_Gear_param.m** script.
-This will define and save all the motor parameters (e.g., pole-pairs, ferromagnetic pole-piece, flux linkage etc..) into the MATLAB workspace.

Ensure there are no errors during execution. If successful, the workspace will contain all the necessary variables for the Simulink model.

## 4.  Open and Run the Simulink File (**Motoring_Gear.slx**)

Open the Motoring_Gear.slx file in Simulink.
This file contains the block diagram of the electric motor system, including the stator, modulator, and rotor dynamics.

Ensure that the Simulink model is correctly linked to the workspace variables (this should happen automatically if **Motoring_Gear_param.m** was run first).

## 5. Set Input Parameters

In the Simulink model, you can set input parameters such as:

-Voltage input to the motor.
-Load torque applied to the rotor.
-Other control inputs (if applicable).

These inputs can be adjusted in the relevant blocks of the Simulink model.

## 6. Run the Simulation

Configure the simulation settings (e.g., simulation time, solver type) in Simulink.

Run the simulation by clicking the Run button.

The simulation will use the parameters from the workspace and the input settings to compute the motor's behavior.

## 7. Analyze Output Data

After the simulation completes, analyze the output data, such as:

Speed of each rotor and Torques etc...

MATLAB will plotting all this data to visualize the results.

Export the data for further analysis if needed.
---

## Contact Information

For questions or issues, please contact:

Name: Edlin

LINE ID: bcbc0507

LinkedIn: https://www.linkedin.com/in/edlin-variste-12376b219/

Email: edlin.variste8@gmail.com

Tel: +886-9-71715-086

Institution: National Cheng Kung University, Electric Motor Technology Research Center (EMTRC).





This README provides a comprehensive guide to using the MATLAB and Simulink files for analyzing the electric motor system. By following these steps, you can simulate the motor's behavior, set input parameters, and analyze output data to gain insights into its performance.

