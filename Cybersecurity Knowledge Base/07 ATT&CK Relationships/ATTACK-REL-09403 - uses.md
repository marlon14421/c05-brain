---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1153"
target_object: "T1027.008"
stix_relationship_id: "relationship--60c3e09e-f620-433f-899f-a5103a39c28c"
---
# Relationship 9403: S1153 — uses → T1027.008

**Source object:** [[01 ATT&CK/S1153 - Cuckoo Stealer|S1153: Cuckoo Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.008 - Stripped Payloads|T1027.008: Stripped Payloads]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cuckoo Stealer](https://attack.mitre.org/software/S1153) is a stripped binary payload.(Citation: Kandji Cuckoo April 2024) (Citation: SentinelOne Cuckoo Stealer May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--60c3e09e-f620-433f-899f-a5103a39c28c`.
