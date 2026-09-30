---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0017"
target_object: "T1005"
stix_relationship_id: "relationship--7cea5a77-cfb2-4e14-88da-ca936433ada0"
---
# Relationship 8720: C0017 — uses → T1005

**Source object:** [[01 ATT&CK/C0017 - C0017|C0017: C0017]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0017](https://attack.mitre.org/campaigns/C0017), [APT41](https://attack.mitre.org/groups/G0096) collected information related to compromised machines as well as Personal Identifiable Information (PII) from victim networks.(Citation: Mandiant APT41)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7cea5a77-cfb2-4e14-88da-ca936433ada0`.
