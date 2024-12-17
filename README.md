# fund-stella
Dedicated to enabling the fundraising of higher education

## Overview
This project facilitates fiat-to-crypto donations using Stellar USDC. The flow involves:
1. Fiat onramp via Transak.
2. USDC transfer using Stellar blockchain.

## File Structure
- `config/`: Configuration files.
- `helpers/`: Utility functions for API interactions and config loading.
- `rust/`: Rust-based Soroban contract for USDC transfer.
- `src/`: Main application logic.
- `tests/`: Unit tests for the project.
- `scripts/`: Shell scripts for building Rust contracts.

## Setup
1. Install Python dependencies:
   ```bash
   pip install -r requirements.txt

