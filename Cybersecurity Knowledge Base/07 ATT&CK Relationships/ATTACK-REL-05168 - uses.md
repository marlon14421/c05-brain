---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0055"
target_object: "T1055.001"
stix_relationship_id: "relationship--22a75bbf-5490-40cb-bdb7-a0eda5e95d21"
---
# Relationship 5168: S0055 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0055 - RARSTONE|S0055: RARSTONE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

After decrypting itself in memory, [RARSTONE](https://attack.mitre.org/software/S0055) downloads a DLL file from its C2 server and loads it in the memory space of a hidden Internet Explorer process. This “downloaded” file is actually not dropped onto the system.(Citation: Camba RARSTONE)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--22a75bbf-5490-40cb-bdb7-a0eda5e95d21`.
