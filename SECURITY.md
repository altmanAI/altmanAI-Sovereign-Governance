# SECURITY.md — Sovereign Governance Security Policy
**Version:** v1.0.0 • **Date:** September 24, 2025

## Scope
Applies to all materials in `Sovereign-Governance` and connected systems (AltmanCore-OS, TrustGPT, Registry).

## Data Handling
- Classify as: Public, Internal, Confidential, Sovereign-Restricted (SR)
- SR materials require key-auth, encryption at rest (AES-256) and in transit (TLS 1.3+)

## Incident Response
1. Identify & contain (within 2 hours of detection)  
2. Preserve evidence and hashes  
3. Notify Sovereign Commander and Legal (TrustGPT)  
4. Patch, retest, and issue Registry entry with changelog

## Vulnerability Disclosure
Email private report to security@altmanfamilygroup.example (placeholder). Do **not** open public issues for SR materials.

## AI Safety
- No training on SR data.  
- Enforce policy checks via TrustGPT-Legal-Layer.  
- Log all high-risk actions to AltmanCore-OS.
