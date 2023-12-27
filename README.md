# CPU Spike Simulation Script

## Overview

This Python script demonstrates a simple way to simulate a CPU spike, allowing users to test and observe system behavior under high CPU utilization. The script utilizes a nested loop of arithmetic operations to consume CPU resources and achieve the desired percentage of CPU utilization. The simulation runs for a specified duration, after which it completes and prints a message.

## Usage

### Requirements

- Python 3.x

### Instructions

1. Clone or download the script to your local machine.
2. Ensure you have Python 3.x installed.
3. Open a terminal or command prompt and navigate to the script's directory.
4. Run the script using the following command:

    ```bash
    python cpu_spike_simulation.py
    ```

5. The script will simulate a CPU spike for 30 seconds with 80% CPU utilization by default. You can customize the duration and CPU percentage by modifying the function parameters in the script.

## Customization

You can customize the simulation by adjusting the following parameters:

- `duration`: The duration of the CPU spike simulation in seconds (default is 30 seconds).
- `cpu_percent`: The target CPU utilization percentage during the spike (default is 80%).

Modify the values in the `simulate_cpu_spike` function call to experiment with different CPU utilization scenarios.

```python
# Example: Simulate a CPU spike for 60 seconds with 90% CPU utilization
simulate_cpu_spike(duration=60, cpu_percent=90)
```

## Important Note

This script is intended for educational and testing purposes. Running the script may cause increased CPU usage, so use it responsibly and avoid running it on systems with critical workloads.

## Disclaimer

The authors of this script are not responsible for any potential issues or consequences resulting from the use of this script. Use it at your own risk and only in environments where it is appropriate to simulate increased CPU usage.
