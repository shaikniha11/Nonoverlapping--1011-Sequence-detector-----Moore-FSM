# Nonoverlapping--1011-Sequence-detector-----Moore-FSM
This project implements a non-overlapping sequence detector for the 4-bit binary pattern "1011". In non-overlapping mode, after detecting a complete sequence, the FSM completely resets to the initial state, requiring a fresh start for the next detection. This behavior is essential for applications requiring unique, non-repetitive pattern markers.
- Moore FSM Architecture: Outputs depend only on current state
- One-Hot State Encoding: Fast transitions with simple logic
- Complete Reset After Detection: Prevents overlapping sequences
- Synchronous Design: Single clock domain operation
- Asynchronous Reset: Immediate initialization on system reset
- Glitch-Free Output: Registered output prevents hazards
- Comprehensive Verification: 9+ edge-case test scenarios
- Low Resource Usage: ~10 LUTs, 6 flip-flops
