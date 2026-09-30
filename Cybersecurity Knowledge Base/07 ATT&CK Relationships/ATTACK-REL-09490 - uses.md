---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0487"
target_object: "T1090"
stix_relationship_id: "relationship--75aa57b2-5d2e-49ec-9c26-317b361632c3"
---
# Relationship 9490: S0487 — uses → T1090

**Source object:** [[01 ATT&CK/S0487 - Kessel|S0487: Kessel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kessel](https://attack.mitre.org/software/S0487) can use a proxy during exfiltration if set in the configuration.(Citation: ESET ForSSHe December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75aa57b2-5d2e-49ec-9c26-317b361632c3`.
