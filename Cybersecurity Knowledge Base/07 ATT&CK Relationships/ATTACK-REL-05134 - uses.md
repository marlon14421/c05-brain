---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "T1069.002"
stix_relationship_id: "relationship--409581f2-270d-43ce-8044-34bc09874548"
---
# Relationship 5134: G0049 — uses → T1069.002

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.002 - Domain Groups|T1069.002: Domain Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OilRig](https://attack.mitre.org/groups/G0049) has used net group /domain , net group “domain admins” /domain , and net group “Exchange Trusted Subsystem” /domain to find domain group permission settings.(Citation: Palo Alto OilRig May 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--409581f2-270d-43ce-8044-34bc09874548`.
