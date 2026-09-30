---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1207"
target_object: "T1053.005"
stix_relationship_id: "relationship--4a08a068-209e-40bc-afc2-97cd774a3b89"
---
# Relationship 8812: S1207 — uses → T1053.005

**Source object:** [[01 ATT&CK/S1207 - XLoader|S1207: XLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XLoader](https://attack.mitre.org/software/S1207) can create scheduled tasks for persistence.(Citation: Netskope XLoader 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4a08a068-209e-40bc-afc2-97cd774a3b89`.
