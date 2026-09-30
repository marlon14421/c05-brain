---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0380"
target_object: "T1518.001"
stix_relationship_id: "relationship--7e90117e-0a1b-4320-9b37-54e070c3dc49"
---
# Relationship 6155: S0380 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0380 - StoneDrill|S0380: StoneDrill]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StoneDrill](https://attack.mitre.org/software/S0380) can check for antivirus and antimalware programs.(Citation: Kaspersky StoneDrill 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e90117e-0a1b-4320-9b37-54e070c3dc49`.
