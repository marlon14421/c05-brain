---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0587"
target_object: "T1016"
stix_relationship_id: "relationship--48318986-6d46-436a-b9ff-dd2ac1ab32a2"
---
# Relationship 8188: S0587 — uses → T1016

**Source object:** [[01 ATT&CK/S0587 - Penquin|S0587: Penquin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Penquin](https://attack.mitre.org/software/S0587) can report the IP of the compromised host to attacker controlled infrastructure.(Citation: Leonardo Turla Penquin May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48318986-6d46-436a-b9ff-dd2ac1ab32a2`.
