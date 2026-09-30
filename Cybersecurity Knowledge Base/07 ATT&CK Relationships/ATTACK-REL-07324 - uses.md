---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0014"
target_object: "T1021.002"
stix_relationship_id: "relationship--82e1cb6f-7528-430f-8e8e-fc3213f25402"
---
# Relationship 7324: C0014 — uses → T1021.002

**Source object:** [[01 ATT&CK/C0014 - Operation Wocao|C0014: Operation Wocao]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Wocao](https://attack.mitre.org/campaigns/C0014), threat actors used [Impacket](https://attack.mitre.org/software/S0357)'s smbexec.py as well as accessing the C$ and IPC$ shares to move laterally.(Citation: FoxIT Wocao December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--82e1cb6f-7528-430f-8e8e-fc3213f25402`.
