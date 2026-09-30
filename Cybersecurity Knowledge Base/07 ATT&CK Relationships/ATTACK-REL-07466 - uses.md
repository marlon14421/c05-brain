---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0409"
target_object: "T1036.005"
stix_relationship_id: "relationship--72cb3a93-f4c1-43a8-9a62-43bf1f6f4889"
---
# Relationship 7466: S0409 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0409 - Machete|S0409: Machete]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Machete](https://attack.mitre.org/software/S0409) renamed payloads to masquerade as legitimate Google Chrome, Java, Dropbox, Adobe Reader and Python executables.(Citation: ESET Machete July 2019)(Citation: Securelist Machete Aug 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--72cb3a93-f4c1-43a8-9a62-43bf1f6f4889`.
