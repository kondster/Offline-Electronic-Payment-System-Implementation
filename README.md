# Offline-Electronic-Payment-System-Implementation
Implementation of A Simplified Scheme for Secure Offline Electronic Payment Systems," published in High-Confidence Computing, 2021

```markdown
# Offline Electronic Payment System Implementation

This repository contains the implementation of an innovative offline electronic payment system, as presented in our project report. The system leverages Schnorr’s untraceable blind signature to provide a secure, anonymous, and practical solution for electronic transactions without the need for constant connectivity.

## Overview

The project aims to address the critical security requirements of e-payment systems through simplified computations, enhancing both practicality and security compared to existing systems. It primarily focuses on ensuring the anonymity and untraceability of transactions, which are key concerns in digital payment systems today.

## Features

- **Schnorr’s Blind Signature**: Utilizes Schnorr’s blind signature to ensure the untraceability and anonymity of the users involved in the transactions.
- **RSA Encryption**: Employs RSA algorithm to securely handle key management and transaction verification.
- **Offline Functionality**: Operates without the need for real-time connectivity to a bank or central authority, thereby reducing system congestion and enhancing privacy.
- **E-coin Management**: Implements features like e-coin generation, verification, and transaction handling with embedded security measures to prevent fraud and multiple spending.

## Repository Structure

- `DataSecurityProject.ipynb` - Jupyter notebook containing the core implementation of the payment system protocols and cryptographic operations.
- `DS_project_report.pdf` - Detailed report explaining the theoretical background, system design, and security analysis of the implemented e-payment scheme.

## Setup and Running

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Libraries: pycryptodome, pandas (Install using pip if necessary)

### Instructions

1. Clone the repository:
   ```
   git clone https://github.com/your-github-username/offline-e-payment-system.git
   ```
2. Navigate to the cloned directory:
   ```
   cd offline-e-payment-system
   ```
3. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```
4. Open the `DataSecurityProject.ipynb` notebook and run the cells to see the implementation in action.

## Contributing

Contributions to enhance the functionality or improve the security features are welcome. Please fork the repository and submit a pull request with your changes. Make sure to provide a detailed description of your improvements or fixes.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
