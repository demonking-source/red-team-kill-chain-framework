# Kill Chain Phases

This document outlines the core phases of the multi-domain red team kill chain framework.

## Phase 1: Reconnaissance
Gather intelligence on targets, infrastructure, and trust relationships using OSINT and scanning techniques.

## Phase 2: Initial Access & Propagation
Gain initial foothold and leverage compromised trusted relationships to expand access (supply-chain style propagation).

## Phase 3: C2 Establishment
Deploy and maintain command and control infrastructure with strong OPSEC considerations (isolated environments, custom profiles, etc.).

## Phase 4: Multi-Layer Defense Evasion
Combine techniques across network, host, and behavioral layers to reduce detection risk.

## Phase 5: Execution & Post-Exploitation
Perform actions on objectives using living-off-the-land techniques, privilege escalation, and data collection.

## Phase 6: Lateral Movement
Expand access within the environment using established channels and previously compromised trust relationships.

## Phase 7: Data Exfiltration
Securely collect and move data out of the target environment while managing detection risk.

## Phase 8: OPSEC & Cleanup
Remove traces and return systems to a clean state after operations. Strong emphasis on minimizing forensic footprint.

---

**Note:** This framework is iterative. Teams can loop between phases as needed rather than following a strict linear path.