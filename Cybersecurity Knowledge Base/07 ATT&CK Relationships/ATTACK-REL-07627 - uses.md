---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0085"
target_object: "T1136.001"
stix_relationship_id: "relationship--6d819560-bdfb-4e0a-bf56-fddcba60cdb5"
---
# Relationship 7627: S0085 — uses → T1136.001

**Source object:** [[01 ATT&CK/S0085 - S-Type|S0085: S-Type]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1136.001 - Local Account|T1136.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[S-Type](https://attack.mitre.org/software/S0085) may create a temporary user on the system named `Lost_{Unique Identifier}` with the password `pond~!@6”{Unique Identifier}`.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6d819560-bdfb-4e0a-bf56-fddcba60cdb5`.
