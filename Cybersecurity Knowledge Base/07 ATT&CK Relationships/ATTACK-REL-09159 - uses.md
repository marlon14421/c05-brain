---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1209"
target_object: "T1125"
stix_relationship_id: "relationship--a4485212-aea0-4cf0-b7f1-79b3048d910f"
---
# Relationship 9159: S1209 — uses → T1125

**Source object:** [[01 ATT&CK/S1209 - Quick Assist|S1209: Quick Assist]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Quick Assist](https://attack.mitre.org/software/S1209) allows for the remote administrator to view the interactive session of the running machine, including full screen activity.(Citation: Microsoft Quick Assist 2024)(Citation: Microsoft Storm-1811 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a4485212-aea0-4cf0-b7f1-79b3048d910f`.
