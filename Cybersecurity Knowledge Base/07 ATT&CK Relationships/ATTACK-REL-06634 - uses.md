---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1218"
stix_relationship_id: "relationship--883e2f79-5bf5-4e08-bb83-f1cd36907958"
---
# Relationship 6634: G0032 — uses → T1218

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218 - System Binary Proxy Execution|T1218: System Binary Proxy Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) lnk files used for persistence have abused the Windows Update Client ( wuauclt.exe ) to execute a malicious DLL.(Citation: Lazarus APT January 2022)(Citation: Qualys LolZarus)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--883e2f79-5bf5-4e08-bb83-f1cd36907958`.
