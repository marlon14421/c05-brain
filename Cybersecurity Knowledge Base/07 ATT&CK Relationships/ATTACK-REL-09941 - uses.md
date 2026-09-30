---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1205"
stix_relationship_id: "relationship--7ad7a5f3-8c10-4677-b0ce-f41fbb6f0306"
---
# Relationship 9941: S9043 — uses → T1205

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205 - Traffic Signaling|T1205: Traffic Signaling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has examined commit messages for a keyword followed by base64 encoded segments to validate communications and to execute subsequent actions to include exfiltration.(Citation: Hunt.io TeamPCP Toolkit MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ad7a5f3-8c10-4677-b0ce-f41fbb6f0306`.
