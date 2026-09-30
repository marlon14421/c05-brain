---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0331"
target_object: "T1113"
stix_relationship_id: "relationship--08109d9e-3258-4b9b-8e1d-ea90d05c18b9"
---
# Relationship 7502: S0331 — uses → T1113

**Source object:** [[01 ATT&CK/S0331 - Agent Tesla|S0331: Agent Tesla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agent Tesla](https://attack.mitre.org/software/S0331) can capture screenshots of the victim’s desktop.(Citation: Talos Agent Tesla Oct 2018)(Citation: DigiTrust Agent Tesla Jan 2017)(Citation: Fortinet Agent Tesla April 2018)(Citation: Fortinet Agent Tesla June 2017)(Citation: Bitdefender Agent Tesla April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08109d9e-3258-4b9b-8e1d-ea90d05c18b9`.
