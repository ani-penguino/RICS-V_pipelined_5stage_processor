# VeriSimpleV Hazard Resolution and Forwarding Logic

## Project Overview
This project enhances the VeriSimpleV processor by implementing comprehensive hazard resolution and forwarding logic. The goal is to optimize the pipeline to handle structural hazards, control hazards, and data hazards, as detailed in the coursework.

## Key Features
- **Structural Hazard Handling**: Implements stalling logic to manage shared memory access between the IF and MEM stages, ensuring MEM stage priority in case of conflict.
- **Control Hazard Resolution**: Predicts branches as not taken and squashes instructions if the prediction is incorrect.
- **Data Forwarding**: Forwards most data dependencies into the EX stage to minimize stalls and maximize pipeline efficiency.
- **Data Hazard Management**: Stalls instructions in the ID stage when data dependencies cannot be forwarded in time.

## Getting Started
To get started with this project, you will need to have a SystemVerilog-compatible simulation environment and an understanding of the VeriSimpleV processor architecture.

### Prerequisites
- SystemVerilog simulation tool (e.g., ModelSim, VCS, or Icarus Verilog)
- Knowledge of pipelined processor architecture and VeriSimpleV processor

### Installation and Setup
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Compile the SystemVerilog files using your preferred simulation tool.

### Running Simulations
Run the simulation with the provided test cases to verify the hazard resolution and forwarding logic. Check the output against the expected results in the `correct_out/` directory.

## Contact
If you have any questions or comments about this project, please open an issue on the GitHub repository page or contact the repository owner directly.

