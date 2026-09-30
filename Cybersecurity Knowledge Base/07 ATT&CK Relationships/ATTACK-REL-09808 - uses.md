---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0022"
target_object: "T1008"
stix_relationship_id: "relationship--a7005b59-48e5-4852-90f7-ed8d2c3698fa"
---
# Relationship 9808: S0022 — uses → T1008

**Source object:** [[01 ATT&CK/S0022 - Uroburos|S0022: Uroburos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Uroburos](https://attack.mitre.org/software/S0022) can use up to 10 channels to communicate between implants.(Citation: Joint Cybersecurity Advisory AA23-129A Snake Malware May 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a7005b59-48e5-4852-90f7-ed8d2c3698fa`.
