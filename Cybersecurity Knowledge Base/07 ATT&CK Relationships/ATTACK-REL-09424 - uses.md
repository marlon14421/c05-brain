---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0087"
target_object: "T1190"
stix_relationship_id: "relationship--fab9f76e-570c-4235-8045-dec89714d435"
---
# Relationship 9424: G0087 — uses → T1190

**Source object:** [[01 ATT&CK/G0087 - APT39|G0087: APT39]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT39](https://attack.mitre.org/groups/G0087) has used SQL injection for initial compromise.(Citation: Symantec Chafer February 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fab9f76e-570c-4235-8045-dec89714d435`.
