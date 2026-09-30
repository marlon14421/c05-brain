---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0049"
target_object: "T1078.002"
stix_relationship_id: "relationship--250eabe6-6a1f-4c07-a5d4-5d1aceb3a961"
---
# Relationship 6799: C0049 — uses → T1078.002

**Source object:** [[01 ATT&CK/C0049 - Leviathan Australian Intrusions|C0049: Leviathan Australian Intrusions]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.002 - Domain Accounts|T1078.002: Domain Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Leviathan](https://attack.mitre.org/groups/G0065) compromised domain credentials during [Leviathan Australian Intrusions](https://attack.mitre.org/campaigns/C0049).(Citation: CISA Leviathan 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--250eabe6-6a1f-4c07-a5d4-5d1aceb3a961`.
