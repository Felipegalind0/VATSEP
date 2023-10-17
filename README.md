# VATSEP (Variable AoA Toroidal Span-Efficient Propeller)

## Innovating Aerodynamic Efficiency in Propeller Design
![Build Status](https://img.shields.io/badge/Build-Passing-green)
![License: CC BY-NC](https://img.shields.io/badge/License-CC%20BY--NC-blue.svg)


---

### Table of Contents
1. [Introduction](#introduction)
2. [Key Features](#key-features)
3. [Installation and Setup](#installation-and-setup)
4. [Usage](#usage)
5. [Technical Details](#technical-details)
6. [Validation and Performance Metrics](#validation-and-performance-metrics)
7. [Use Cases](#use-cases)
8. [Contributing](#contributing)
9. [License](#license)
10. [Acknowledgments](#acknowledgments)
11. [Contact Information](#contact-information)
12. [Updates](#updates)

---

## Introduction
VATSEP aims to redefine propeller efficiency with a Variable Angle of Attack and Toroidal design that optimizes lift across the entire span.

---

## Key Features
- **Variable Angle of Attack (AoA)**
- **Toroidal Shape**
- **Span Efficiency**

![VATSEP Diagram](./images/VATSEP_diagram.png)

---

## Installation and Setup

### Prerequisites
- SolidWorks or any other compatible CAD software.

### Quick Start
```bash
git clone https://github.com/YourUsername/VATSEP.git
cd scripts/
./setup.sh
```

---

## Usage

### Manual Setup
Open the CAD files using SolidWorks or import into a CFD simulator of choice.

### Automated Simulation
Run `./run_simulation.sh` from the `scripts/` directory.

---

## Technical Details
Detailed technical discussions can be found in the [Wiki](https://github.com/YourUsername/VATSEP/wiki).

### NACA Profile
Utilizes NACA 24 12 for optimal aerodynamic performance.

### AoA
Variable angle from 30° (center) to 10° (tip).

### Span Efficiency
Maximizes lift across the blade span.

---

## Validation and Performance Metrics

| Metric        | VATSEP          | Standard Propeller  |
| ------------- |:---------------:| ------------------:|
| Thrust        | TBD             | TBD                |
| Efficiency    | TBD             | TBD                |

### CFD Results
See `/results/CFD/` for simulation outcomes.

---

## Use Cases
- Drones
- Wind turbines
- Marine propulsion

---

## Contributing
Refer to [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

---

## License
See [LICENSE.md](./LICENSE.md) for details.

---

## Acknowledgments
Thanks to the open-source aerodynamics community for valuable insights.

---

## Contact Information
For inquiries or collaborations, contact [Your Email].

---

## Updates
- Added CFD simulation scripts (Oct 17, 2023)
- Initial commit (Oct 15, 2023)
