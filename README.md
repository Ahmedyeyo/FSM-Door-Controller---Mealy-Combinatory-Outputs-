
---

### **FSM Door Controller - Mealy (Combinatory Outputs)**

```markdown
# FSM Door Controller - Mealy (Combinatory Outputs)

## Project Overview
This project leverages the Mealy model to implement a Finite State Machine (FSM) for door control. The design combines state logic with real-time input responsiveness to produce efficient and adaptive door control systems. Outputs in this model are combinatory, directly influenced by both the state and input signals, making it faster for certain real-world scenarios.

## Features
- **Mealy Model**: Dynamic and responsive design where outputs depend on both the current state and active inputs.
- **Combinatory Outputs**: Rapid response to input changes without requiring a full state transition.
- **Efficient Design**: Optimized state transitions to handle complex input scenarios effectively.
- **Validated Design**: Simulations confirm the FSM's ability to handle various door control use cases.

## Applications
- Adaptive door systems in hospitals and retail spaces.
- Entry and exit gates in secure facilities.
- Systems requiring fast responses to sensor inputs.

## File Structure
- **src/**: VHDL source files for the Mealy FSM with combinatory outputs.
- **doc/**: Includes detailed design specifications and the results of simulation tests.
- **simulation/**: Contains simulation waveforms, validation logs, and test scenarios.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/FSM_Door_Controller_Mealy_Combinatory.git
