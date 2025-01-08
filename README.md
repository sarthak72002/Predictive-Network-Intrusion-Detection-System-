
# Cybersecurity Analytics and Threat Simulation

This project focuses on analyzing and simulating cybersecurity threats using a dataset containing network traffic and attack patterns. The project leverages data science and machine learning techniques to detect and classify various cyberattacks.

## Project Overview

The project aims to:

- Identify and analyze key features of network traffic.
- Simulate various attack scenarios.
- Build predictive models to classify normal and attack records.

## Dataset Description

The dataset contains detailed records of network traffic, including:

- **Source and Destination Information**: IP addresses, ports, and transaction protocols.
- **Traffic Metrics**: Bytes transferred, packet counts, and jitter.
- **Connection Information**: TCP window values, connection round-trip times, and interpacket arrival times.
- **Attack Categories**: Labels indicating normal or attack records across categories like DoS, Exploits, Fuzzers, Worms, and others.

### Key Features in the Dataset

- `srcip`: Source IP address
- `dstip`: Destination IP address
- `sbytes`: Bytes transferred from source to destination
- `dbytes`: Bytes transferred from destination to source
- `attack_cat`: Name of the attack category
- `Label`: Binary indicator (0 for normal, 1 for attack)

_For a full list of features, refer to the notebook._

## Technologies Used

- **Programming Language**: Python
- **Libraries**: pandas, NumPy, scikit-learn, matplotlib, seaborn, etc.
- **Tools**: Jupyter Notebook, Visual Studio Code

## Getting Started

### Prerequisites

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

### Running the Project

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Open the notebook in Jupyter:

```bash
jupyter notebook "Capstone Project Group 3.ipynb"
```

3. Follow the instructions in the notebook to explore and run the analysis.

## Contributors

- [Sarthak]  
- [Suvrat, Amrendra, Prapti]

## License

This project is licensed under the MIT License. See the LICENSE file for details.
