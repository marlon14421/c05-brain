---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1035"
target_object: "T1020"
stix_relationship_id: "relationship--a16a3223-06a6-453d-b044-f683bda1bf2a"
---
# Relationship 8881: G1035 — uses → T1020

**Source object:** [[01 ATT&CK/G1035 - Winter Vivern|G1035: Winter Vivern]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1020 - Automated Exfiltration|T1020: Automated Exfiltration]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Winter Vivern](https://attack.mitre.org/groups/G1035) delivered a PowerShell script capable of recursively scanning victim machines looking for various file types before exfiltrating identified files via HTTP.(Citation: CERT-UA WinterVivern 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a16a3223-06a6-453d-b044-f683bda1bf2a`.
