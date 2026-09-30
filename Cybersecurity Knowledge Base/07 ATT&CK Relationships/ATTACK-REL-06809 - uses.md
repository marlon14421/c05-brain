---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9009"
target_object: "T1528"
stix_relationship_id: "relationship--aea68064-afb4-4748-9b7b-f10113f347ab"
---
# Relationship 6809: S9009 — uses → T1528

**Source object:** [[01 ATT&CK/S9009 - TruffleHog|S9009: TruffleHog]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1528 - Steal Application Access Token|T1528: Steal Application Access Token]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TruffleHog](https://attack.mitre.org/software/S9009) has gathered access tokens and API tokens from CI/CD pipeline solutions and repositories.(Citation: Black Hills Information Security TruffleHog January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aea68064-afb4-4748-9b7b-f10113f347ab`.
