---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0024"
target_object: "T1550"
stix_relationship_id: "relationship--2a8a7397-8977-4554-abbf-5168074cd4cc"
---
# Relationship 5820: C0024 — uses → T1550

**Source object:** [[01 ATT&CK/C0024 - SolarWinds Compromise|C0024: SolarWinds Compromise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1550 - Use Alternate Authentication Material|T1550: Use Alternate Authentication Material]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024), [APT29](https://attack.mitre.org/groups/G0016) used forged SAML tokens that allowed the actors to impersonate users and bypass MFA, enabling [APT29](https://attack.mitre.org/groups/G0016) to access enterprise cloud applications and services.(Citation: Microsoft 365 Defender Solorigate)(Citation: Secureworks IRON RITUAL Profile)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2a8a7397-8977-4554-abbf-5168074cd4cc`.
