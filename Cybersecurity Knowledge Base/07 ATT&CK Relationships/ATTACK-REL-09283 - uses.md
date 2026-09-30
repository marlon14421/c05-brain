---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0073"
target_object: "T1033"
stix_relationship_id: "relationship--331ebf73-af72-4121-815a-d10392ac75ab"
---
# Relationship 9283: G0073 — uses → T1033

**Source object:** [[01 ATT&CK/G0073 - APT19|G0073: APT19]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT19](https://attack.mitre.org/groups/G0073) used an HTTP malware variant and a Port 22 malware variant to collect the victim’s username.(Citation: Unit 42 C0d0so0 Jan 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--331ebf73-af72-4121-815a-d10392ac75ab`.
