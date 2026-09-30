---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1587.001"
stix_relationship_id: "relationship--062f7bee-8b54-4edd-aca9-11437b7cbc8b"
---
# Relationship 5247: G0094 — uses → T1587.001

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.001 - Malware|T1587.001: Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has developed its own unique malware such as MailFetch.py for use in operations.(Citation: KISA Operation Muzabi)(Citation: Talos Kimsuky Nov 2021)(Citation: Mandiant APT43 March 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--062f7bee-8b54-4edd-aca9-11437b7cbc8b`.
