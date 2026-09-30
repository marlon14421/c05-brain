---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0136"
target_object: "T1119"
stix_relationship_id: "relationship--7a892ca0-f915-4dc1-817a-cdcfb6777f28"
---
# Relationship 8704: S0136 — uses → T1119

**Source object:** [[01 ATT&CK/S0136 - USBStealer|S0136: USBStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For all non-removable drives on a victim, [USBStealer](https://attack.mitre.org/software/S0136) executes automated collection of certain files for later exfiltration.(Citation: ESET Sednit USBStealer 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a892ca0-f915-4dc1-817a-cdcfb6777f28`.
