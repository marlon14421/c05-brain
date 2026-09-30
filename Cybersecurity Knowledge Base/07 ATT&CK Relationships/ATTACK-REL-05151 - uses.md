---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0143"
target_object: "T1011.001"
stix_relationship_id: "relationship--2858ec3b-5814-4515-9dda-f8009fbf4cd3"
---
# Relationship 5151: S0143 — uses → T1011.001

**Source object:** [[01 ATT&CK/S0143 - Flame|S0143: Flame]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1011.001 - Exfiltration Over Bluetooth|T1011.001: Exfiltration Over Bluetooth]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Flame](https://attack.mitre.org/software/S0143) has a module named BeetleJuice that contains Bluetooth functionality that may be used in different ways, including transmitting encoded information from the infected system over the Bluetooth protocol, acting as a Bluetooth beacon, and identifying other Bluetooth devices in the vicinity.(Citation: Symantec Beetlejuice)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2858ec3b-5814-4515-9dda-f8009fbf4cd3`.
