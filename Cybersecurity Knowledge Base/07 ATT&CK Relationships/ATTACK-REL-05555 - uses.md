---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0144"
target_object: "T1082"
stix_relationship_id: "relationship--a08dadbf-6f68-415f-9daa-f84571af83a2"
---
# Relationship 5555: S0144 — uses → T1082

**Source object:** [[01 ATT&CK/S0144 - ChChes|S0144: ChChes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ChChes](https://attack.mitre.org/software/S0144) collects the victim hostname, window resolution, and Microsoft Windows version.(Citation: Palo Alto menuPass Feb 2017)(Citation: PWC Cloud Hopper Technical Annex April 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a08dadbf-6f68-415f-9daa-f84571af83a2`.
