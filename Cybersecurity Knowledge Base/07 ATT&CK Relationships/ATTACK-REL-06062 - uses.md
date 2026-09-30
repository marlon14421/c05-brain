---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0211"
target_object: "T1005"
stix_relationship_id: "relationship--d6049a18-43d5-4761-ad56-a60e2a7998cf"
---
# Relationship 6062: S0211 — uses → T1005

**Source object:** [[01 ATT&CK/S0211 - Linfo|S0211: Linfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Linfo](https://attack.mitre.org/software/S0211) creates a backdoor through which remote attackers can obtain data from local systems.(Citation: Symantec Linfo May 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d6049a18-43d5-4761-ad56-a60e2a7998cf`.
