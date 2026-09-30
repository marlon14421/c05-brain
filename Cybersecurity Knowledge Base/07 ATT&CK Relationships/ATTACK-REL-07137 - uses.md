---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0161"
target_object: "T1071.002"
stix_relationship_id: "relationship--785abba4-fdb4-4aad-9049-5a0c748cc965"
---
# Relationship 7137: S0161 — uses → T1071.002

**Source object:** [[01 ATT&CK/S0161 - XAgentOSX|S0161: XAgentOSX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.002 - File Transfer Protocols|T1071.002: File Transfer Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XAgentOSX](https://attack.mitre.org/software/S0161) contains the ftpUpload function to use the FTPManager:uploadFile method to upload files from the target system.(Citation: XAgentOSX 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--785abba4-fdb4-4aad-9049-5a0c748cc965`.
