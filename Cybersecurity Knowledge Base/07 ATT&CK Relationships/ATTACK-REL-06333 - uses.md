---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0362"
target_object: "T1033"
stix_relationship_id: "relationship--9613ad57-7f24-4dff-bea3-2626d8b2c335"
---
# Relationship 6333: S0362 — uses → T1033

**Source object:** [[01 ATT&CK/S0362 - Linux Rabbit|S0362: Linux Rabbit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Linux Rabbit](https://attack.mitre.org/software/S0362) opens a socket on port 22 and if it receives a response it attempts to obtain the machine's hostname and Top-Level Domain. (Citation: Anomali Linux Rabbit 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9613ad57-7f24-4dff-bea3-2626d8b2c335`.
