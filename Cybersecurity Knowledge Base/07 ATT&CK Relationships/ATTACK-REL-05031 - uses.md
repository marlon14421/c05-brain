---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9024"
target_object: "T1040"
stix_relationship_id: "relationship--aa03a8fe-d67f-43b8-8108-c877734044e5"
---
# Relationship 5031: S9024 — uses → T1040

**Source object:** [[01 ATT&CK/S9024 - SPAWNCHIMERA|S9024: SPAWNCHIMERA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SPAWNCHIMERA](https://attack.mitre.org/software/S9024) has monitored and filtered network traffic on compromised edge devices, allowing legitimate traffic to pass while redirecting attacker-controlled traffic to infrastructure under adversary control. (Citation: Google UNC5221 Ivanti January 2025)(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aa03a8fe-d67f-43b8-8108-c877734044e5`.
