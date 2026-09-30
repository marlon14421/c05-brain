---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0006"
target_object: "T1105"
stix_relationship_id: "relationship--c9d15fcf-d9f2-4f03-aabf-0e84523efc2b"
---
# Relationship 6935: C0006 — uses → T1105

**Source object:** [[01 ATT&CK/C0006 - Operation Honeybee|C0006: Operation Honeybee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Honeybee](https://attack.mitre.org/campaigns/C0006), the threat actors downloaded additional malware and malicious scripts onto a compromised host.(Citation: McAfee Honeybee)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c9d15fcf-d9f2-4f03-aabf-0e84523efc2b`.
