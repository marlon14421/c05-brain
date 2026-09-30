---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9013"
target_object: "T1489"
stix_relationship_id: "relationship--ed0f49d3-fe2e-48fd-bc45-65f0de468a50"
---
# Relationship 9637: S9013 — uses → T1489

**Source object:** [[01 ATT&CK/S9013 - DRYHOOK|S9013: DRYHOOK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DRYHOOK](https://attack.mitre.org/software/S9013) has terminated all instances of the `cgi-server` process before activating the modified DSAuth.pm file.(Citation: Google UNC5221 Ivanti January 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed0f49d3-fe2e-48fd-bc45-65f0de468a50`.
