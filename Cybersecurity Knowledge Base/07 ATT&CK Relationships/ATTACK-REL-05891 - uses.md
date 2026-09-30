---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1228"
target_object: "T1048.003"
stix_relationship_id: "relationship--e2498e90-b4dc-4ef4-b1e5-d34537a2f4b2"
---
# Relationship 5891: S1228 — uses → T1048.003

**Source object:** [[01 ATT&CK/S1228 - PUBLOAD|S1228: PUBLOAD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048.003 - Exfiltration Over Unencrypted Non-C2 Protocol|T1048.003: Exfiltration Over Unencrypted Non-C2 Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PUBLOAD](https://attack.mitre.org/software/S1228) has leveraged `curl` for data exfiltration over FTP by uploading RAR archives containing targeted files (.doc, .docx, .xls, .xlsx, .pdf, .ppt, .pptx) to an adversary-owned FTP site.(Citation: Trend Micro MUSTANG PANDA PUBLOAD HIUPAN SEPTEMBER 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2498e90-b4dc-4ef4-b1e5-d34537a2f4b2`.
