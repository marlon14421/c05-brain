---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9034"
target_object: "T1082"
stix_relationship_id: "relationship--c97ef137-79d7-4e87-ba15-f719724eb15b"
---
# Relationship 6984: S9034 — uses → T1082

**Source object:** [[01 ATT&CK/S9034 - Tsundere Botnet|S9034: Tsundere Botnet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tsundere Botnet](https://attack.mitre.org/software/S9034) has collected the machine’s MAC address, total memory, GPU information and other system information.(Citation: SecureListUbiedo_Tsundere_Nov2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c97ef137-79d7-4e87-ba15-f719724eb15b`.
