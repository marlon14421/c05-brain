---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9034"
target_object: "T1059.007"
stix_relationship_id: "relationship--87a6c355-530c-4c68-a435-f83565000e95"
---
# Relationship 7906: S9034 — uses → T1059.007

**Source object:** [[01 ATT&CK/S9034 - Tsundere Botnet|S9034: Tsundere Botnet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tsundere Botnet](https://attack.mitre.org/software/S9034) has the ability to run JavaScript code from the C2 server. Additionally, [Tsundere Botnet](https://attack.mitre.org/software/S9034) has used Node.js to execute JavaScript code for the loader component.(Citation: SecureListUbiedo_Tsundere_Nov2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87a6c355-530c-4c68-a435-f83565000e95`.
