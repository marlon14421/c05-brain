---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0208"
target_object: "T1680"
stix_relationship_id: "relationship--5bdc87b7-a975-4fd8-a4e3-131f769600f3"
---
# Relationship 9233: S0208 — uses → T1680

**Source object:** [[01 ATT&CK/S0208 - Pasam|S0208: Pasam]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pasam](https://attack.mitre.org/software/S0208) creates a backdoor through which remote attackers can retrieve information like free disk space.(Citation: Symantec Pasam May 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5bdc87b7-a975-4fd8-a4e3-131f769600f3`.
