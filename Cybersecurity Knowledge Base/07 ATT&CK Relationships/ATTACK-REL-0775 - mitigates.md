---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1035"
target_object: "T1021"
stix_relationship_id: "relationship--3a062b27-636e-4164-9156-65631d140765"
---
# Relationship 0775: M1035 — mitigates → T1021

**Source object:** [[01 ATT&CK/M1035 - Limit Access to Resource Over Network|M1035: Limit Access to Resource Over Network]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1021 - Remote Services|T1021: Remote Services]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Prevent unnecessary remote access to file shares, hypervisors, sensitive systems, etc. Mechanisms to limit access may include use of network concentrators, RDP gateways, etc.(Citation: Sygnia ESXi Ransomware 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a062b27-636e-4164-9156-65631d140765`.
