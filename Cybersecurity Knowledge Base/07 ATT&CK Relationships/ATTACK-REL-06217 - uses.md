---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0455"
target_object: "T1056.001"
stix_relationship_id: "relationship--0c2259d0-2d56-4bbc-bd98-e35ac991b6e8"
---
# Relationship 6217: S0455 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0455 - Metamorfo|S0455: Metamorfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Metamorfo](https://attack.mitre.org/software/S0455) has a command to launch a keylogger and capture keystrokes on the victim’s machine.(Citation: Fortinet Metamorfo Feb 2020)(Citation: ESET Casbaneiro Oct 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c2259d0-2d56-4bbc-bd98-e35ac991b6e8`.
