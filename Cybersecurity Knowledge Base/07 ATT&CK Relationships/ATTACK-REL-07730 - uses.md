---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0331"
target_object: "T1218.009"
stix_relationship_id: "relationship--30b4b9c6-1117-4242-80c4-fd7dc7016a08"
---
# Relationship 7730: S0331 — uses → T1218.009

**Source object:** [[01 ATT&CK/S0331 - Agent Tesla|S0331: Agent Tesla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.009 - Regsvcs-Regasm|T1218.009: Regsvcs/Regasm]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agent Tesla](https://attack.mitre.org/software/S0331) has dropped RegAsm.exe onto systems for performing malicious activity.(Citation: SentinelLabs Agent Tesla Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30b4b9c6-1117-4242-80c4-fd7dc7016a08`.
