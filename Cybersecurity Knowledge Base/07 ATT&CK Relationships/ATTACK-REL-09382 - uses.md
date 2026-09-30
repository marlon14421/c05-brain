---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0385"
target_object: "T1686.003"
stix_relationship_id: "relationship--ab464bce-f384-45df-b2b8-7db2be236aa5"
---
# Relationship 9382: S0385 — uses → T1686.003

**Source object:** [[01 ATT&CK/S0385 - njRAT|S0385: njRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1686.003 - Windows Host Firewall|T1686.003: Windows Host Firewall]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[njRAT](https://attack.mitre.org/software/S0385) has modified the Windows firewall to allow itself to communicate through the firewall.(Citation: Fidelis njRAT June 2013)(Citation: Trend Micro njRAT 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ab464bce-f384-45df-b2b8-7db2be236aa5`.
