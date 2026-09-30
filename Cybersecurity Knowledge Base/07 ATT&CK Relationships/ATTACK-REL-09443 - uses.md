---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0001"
target_object: "T1542.001"
stix_relationship_id: "relationship--89cbf71b-9189-43ac-927f-e5aaf9d66df0"
---
# Relationship 9443: S0001 — uses → T1542.001

**Source object:** [[01 ATT&CK/S0001 - Trojan.Mebromi|S0001: Trojan.Mebromi]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1542.001 - System Firmware|T1542.001: System Firmware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Trojan.Mebromi](https://attack.mitre.org/software/S0001) performs BIOS modification and can download and execute a file as well as protect itself from removal.(Citation: Ge 2011)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--89cbf71b-9189-43ac-927f-e5aaf9d66df0`.
