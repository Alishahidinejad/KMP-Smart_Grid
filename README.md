# KMP-Smart-Grid
Welcome to the KMP-Smart-Grid repository, where we present ProVerif automated security verification codes tailored for a key management protocol designed specifically for smart grids. This protocol is equipped with comprehensive process definitions for key entities, namely the Registration Authority (RA), Energy Provider (EP), and Smart Meter (SM).

## Overview
The repository includes four distinct codes designed to test the authentication and key agreement protocol against various attacks in a smart grid scenario. Additionally, it evaluates whether the protocol provides perfect forward secrecy.

## Codes and Testing Scenarios
1. **Testing Common Attacks**
   - This code assesses the authentication and key agreement protocol's resilience against common attacks in a smart grid context.

2. **Testing Key Compromise Impersonation (KCI) Attack**
   - Specifically targeting key compromise impersonation, this code evaluates the protocol's ability to withstand such attacks.

3. **Testing Ephemeral Secret Leakage (ESL) Attack**
   - Focusing on ephemeral secret leakage, this code examines the protocol's resistance to potential threats in this area.

4. **Testing Perfect Forward Secrecy (PFS)**
   - This code is dedicated to testing and verifying the protocol's adherence to the perfect forward secrecy property.

## Obtaining Results
To obtain results for these tests, simply copy and paste the respective code into the ProVerif tool available at http://proverif20.paris.inria.fr/ and run them separately.

Feel free to explore, contribute, and enhance the security verification process for key management protocols in smart grids with ProVerif. We appreciate your interest and collaboration!
