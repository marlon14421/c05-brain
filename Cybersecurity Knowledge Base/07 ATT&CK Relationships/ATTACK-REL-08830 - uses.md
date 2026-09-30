---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0615"
target_object: "T1055.001"
stix_relationship_id: "relationship--d7aa491f-a801-4611-ad07-5096e12c5c5f"
---
# Relationship 8830: S0615 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0615 - SombRAT|S0615: SombRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SombRAT](https://attack.mitre.org/software/S0615) can execute loadfromfile , loadfromstorage , and loadfrommem to inject a DLL from disk, storage, or memory respectively.(Citation: BlackBerry CostaRicto November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d7aa491f-a801-4611-ad07-5096e12c5c5f`.
