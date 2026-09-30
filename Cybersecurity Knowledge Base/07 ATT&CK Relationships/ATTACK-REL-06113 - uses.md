---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1033"
target_object: "T1583"
stix_relationship_id: "relationship--c430932c-65d1-4f27-994b-fdf39220e530"
---
# Relationship 6113: G1033 — uses → T1583

**Source object:** [[01 ATT&CK/G1033 - Star Blizzard|G1033: Star Blizzard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583 - Acquire Infrastructure|T1583: Acquire Infrastructure]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Star Blizzard](https://attack.mitre.org/groups/G1033) has used HubSpot and MailerLite marketing platform services to hide the true sender of phishing emails.(Citation: StarBlizzard)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c430932c-65d1-4f27-994b-fdf39220e530`.
