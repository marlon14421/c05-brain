---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0641"
target_object: "T1074"
stix_relationship_id: "relationship--773e62aa-8b0a-4ed2-9954-1886c789e926"
---
# Relationship 6252: S0641 — uses → T1074

**Source object:** [[01 ATT&CK/S0641 - Kobalos|S0641: Kobalos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074 - Data Staged|T1074: Data Staged]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kobalos](https://attack.mitre.org/software/S0641) can write captured SSH connection credentials to a file under the /var/run directory with a .pid extension for exfiltration.(Citation: ESET Kobalos Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--773e62aa-8b0a-4ed2-9954-1886c789e926`.
