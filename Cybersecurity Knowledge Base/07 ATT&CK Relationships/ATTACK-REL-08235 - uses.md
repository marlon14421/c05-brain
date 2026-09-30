---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0638"
target_object: "T1135"
stix_relationship_id: "relationship--bba92907-b2fd-4f62-b356-63fab9d714dd"
---
# Relationship 8235: S0638 — uses → T1135

**Source object:** [[01 ATT&CK/S0638 - Babuk|S0638: Babuk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Babuk](https://attack.mitre.org/software/S0638) has the ability to enumerate network shares.(Citation: Sogeti CERT ESEC Babuk March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bba92907-b2fd-4f62-b356-63fab9d714dd`.
