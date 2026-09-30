---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1045"
target_object: "T1190"
stix_relationship_id: "relationship--f63e09a1-6ed2-48b4-9ba2-69eec39091b4"
---
# Relationship 9649: G1045 — uses → T1190

**Source object:** [[01 ATT&CK/G1045 - Salt Typhoon|G1045: Salt Typhoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Salt Typhoon](https://attack.mitre.org/groups/G1045) has exploited CVE-2018-0171 in the Smart Install feature of Cisco IOS and Cisco IOS XE software for initial access.(Citation: Cisco Salt Typhoon FEB 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f63e09a1-6ed2-48b4-9ba2-69eec39091b4`.
