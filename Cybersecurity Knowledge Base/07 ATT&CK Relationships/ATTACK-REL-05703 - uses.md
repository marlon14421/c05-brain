---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0053"
target_object: "T1119"
stix_relationship_id: "relationship--55ffbd77-ec97-4dca-9399-b9e4b62fbbf8"
---
# Relationship 5703: G0053 — uses → T1119

**Source object:** [[01 ATT&CK/G0053 - FIN5|G0053: FIN5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN5](https://attack.mitre.org/groups/G0053) scans processes on all victim systems in the environment and uses automated scripts to pull back the results.(Citation: Mandiant FIN5 GrrCON Oct 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--55ffbd77-ec97-4dca-9399-b9e4b62fbbf8`.
