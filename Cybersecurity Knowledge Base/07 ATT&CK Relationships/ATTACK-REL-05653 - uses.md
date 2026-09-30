---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0250"
target_object: "T1055.001"
stix_relationship_id: "relationship--21674a10-7168-420e-b916-2979a3ee3b5e"
---
# Relationship 5653: S0250 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0250 - Koadic|S0250: Koadic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Koadic](https://attack.mitre.org/software/S0250) can perform process injection by using a reflective DLL.(Citation: Github Koadic)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--21674a10-7168-420e-b916-2979a3ee3b5e`.
