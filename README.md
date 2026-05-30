# ProVerif Formal Verification for CROP‑3FA Protocol

This folder contains the ProVerif model that formally verifies the security properties of the **CROP‑3FA** authentication protocol described in the paper:

> *CROP‑3FA: A CRP‑Free PUF and Chaotic Map‑Based Three‑Factor Authentication Protocol with Bilateral KCI Resilience for IIoT*

## File Description

- `implementation.pv` – The ProVerif model implementing the user, gateway, and sensor processes, along with all cryptographic primitives, events, and security queries.

## Requirements

- **ProVerif** version 2.05 or later (tested with 2.06).
- No additional libraries or packages are required.

You can download ProVerif from: [https://proverif.inria.fr/](https://proverif.inria.fr/)

## Running the Verification

From a terminal, run:

```bash
proverif crop3fa.pv
