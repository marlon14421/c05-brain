---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0428"
target_object: "T1497.001"
stix_relationship_id: "relationship--6340a1e8-4880-4c91-b4fd-ce909b35b87f"
---
# Relationship 8172: S0428 — uses → T1497.001

**Source object:** [[01 ATT&CK/S0428 - PoetRAT|S0428: PoetRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PoetRAT](https://attack.mitre.org/software/S0428) checked the size of the hard drive to determine if it was being run in a sandbox environment. In the event of sandbox detection, it would delete itself by overwriting the malware scripts with the contents of "License.txt" and exiting.(Citation: Talos PoetRAT April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6340a1e8-4880-4c91-b4fd-ce909b35b87f`.
