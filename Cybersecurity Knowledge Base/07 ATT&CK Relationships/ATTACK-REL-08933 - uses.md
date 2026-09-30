---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0037"
target_object: "T1095"
stix_relationship_id: "relationship--d6cb7440-c39c-4bc2-b30e-5264a7f8753c"
---
# Relationship 8933: G0037 — uses → T1095

**Source object:** [[01 ATT&CK/G0037 - FIN6|G0037: FIN6]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN6](https://attack.mitre.org/groups/G0037) has used Metasploit Bind and Reverse TCP stagers.(Citation: Trend Micro FIN6 October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d6cb7440-c39c-4bc2-b30e-5264a7f8753c`.
