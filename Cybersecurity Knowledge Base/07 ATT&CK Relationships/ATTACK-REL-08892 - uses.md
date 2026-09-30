---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1146"
target_object: "T1056.001"
stix_relationship_id: "relationship--0dc3db64-17d3-4a1e-9f11-5e974d28db4f"
---
# Relationship 8892: S1146 — uses → T1056.001

**Source object:** [[01 ATT&CK/S1146 - MgBot|S1146: MgBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MgBot](https://attack.mitre.org/software/S1146) includes keylogger payloads focused on the QQ chat application.(Citation: ESET EvasivePanda 2023)(Citation: Symantec Daggerfly 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0dc3db64-17d3-4a1e-9f11-5e974d28db4f`.
