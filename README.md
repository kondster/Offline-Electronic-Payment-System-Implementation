# Offline Electronic Payment System Implementation

This repository contains the implementation of an innovative offline electronic payment system, as described in our project report. The system utilizes Schnorr’s untraceable blind signature to offer a secure, anonymous, and practical solution for electronic transactions without constant connectivity.

## Overview

This project addresses the security requirements of e-payment systems through simplified computations, enhancing both practicality and security compared to existing systems. It focuses on ensuring transaction anonymity and untraceability, critical concerns in digital payment systems today.

## Features

- **Schnorr’s Blind Signature**: Utilizes Schnorr’s blind signature to ensure user anonymity and transaction untraceability.
- **RSA Encryption**: Employs RSA algorithm for secure key management and transaction verification.
- **Offline Functionality**: Operates without real-time connectivity, reducing system congestion and enhancing privacy.
- **E-coin Management**: Implements e-coin generation, verification, and transaction handling with built-in security measures to prevent fraud and double spending.

## Repository Structure

- `project.ipynb`: Jupyter notebook containing the core implementation of payment system protocols and cryptographic operations.
- `DS_project_report.pdf`: Detailed report explaining theoretical background, system design, and security analysis of the e-payment scheme.

## Setup and Running

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: pycryptodome, pandas (Install using pip if necessary)

### Instructions

1. Clone the repository:
git clone https://github.com/your-github-username/offline-e-payment-system.git

2. Navigate to the cloned directory:
cd offline-e-payment-system

3. Start Jupyter Notebook:
jupyter notebook

4. Open the `project.ipynb` notebook and run the cells to see the implementation in action.

## Contributing

Contributions to enhance functionality or improve security features are welcome. Fork the repository and submit a pull request with your changes, providing a detailed description of your improvements or fixes.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

