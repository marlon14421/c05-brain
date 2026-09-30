---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0002"
target_object: "T1558.001"
stix_relationship_id: "relationship--7b8254f2-bfbb-4775-aaf8-3b5fa3457ee9"
---
# Relationship 5085: S0002 — uses → T1558.001

**Source object:** [[01 ATT&CK/S0002 - Mimikatz|S0002: Mimikatz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1558.001 - Golden Ticket|T1558.001: Golden Ticket]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mimikatz](https://attack.mitre.org/software/S0002)'s kerberos module can create golden tickets.(Citation: GitHub Mimikatz kerberos Module)(Citation: Cobalt Strike Manual 4.3 November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b8254f2-bfbb-4775-aaf8-3b5fa3457ee9`.
