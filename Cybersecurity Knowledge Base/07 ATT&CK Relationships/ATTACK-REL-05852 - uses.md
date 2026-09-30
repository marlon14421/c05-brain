---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1013"
target_object: "T1082"
stix_relationship_id: "relationship--16e1777b-af28-412b-bcc3-469aba0f8a87"
---
# Relationship 5852: S1013 — uses → T1082

**Source object:** [[01 ATT&CK/S1013 - ZxxZ|S1013: ZxxZ]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZxxZ](https://attack.mitre.org/software/S1013) has collected the host name and operating system product name from a compromised machine.(Citation: Cisco Talos Bitter Bangladesh May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16e1777b-af28-412b-bcc3-469aba0f8a87`.
