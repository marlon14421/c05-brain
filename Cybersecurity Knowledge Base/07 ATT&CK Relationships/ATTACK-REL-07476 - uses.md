---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0010"
target_object: "T1567.002"
stix_relationship_id: "relationship--7dda2468-0344-48c5-8843-6655084d8159"
---
# Relationship 7476: G0010 — uses → T1567.002

**Source object:** [[01 ATT&CK/G0010 - Turla|G0010: Turla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Turla](https://attack.mitre.org/groups/G0010) has used WebDAV to upload stolen USB files to a cloud drive.(Citation: Symantec Waterbug Jun 2019) [Turla](https://attack.mitre.org/groups/G0010) has also exfiltrated stolen files to OneDrive and 4shared.(Citation: ESET ComRAT May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7dda2468-0344-48c5-8843-6655084d8159`.
