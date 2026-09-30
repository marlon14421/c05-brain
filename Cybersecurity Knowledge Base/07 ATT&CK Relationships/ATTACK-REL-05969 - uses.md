---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1110"
stix_relationship_id: "relationship--c728ccae-df91-4801-824d-2e235269eb8f"
---
# Relationship 5969: G1057 — uses → T1110

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110 - Brute Force|T1110: Brute Force]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has performed brute force attacks against edge devices, such as VPNs or firewall solutions.(Citation: ElecticIQ Buyukkaya_ShinyHunters_Sept2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c728ccae-df91-4801-824d-2e235269eb8f`.
