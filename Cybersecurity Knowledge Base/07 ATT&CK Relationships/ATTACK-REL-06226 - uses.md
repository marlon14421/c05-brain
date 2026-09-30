---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0022"
target_object: "T1071.003"
stix_relationship_id: "relationship--3ce884c7-71c5-4f46-b09c-1abb45d8341b"
---
# Relationship 6226: S0022 — uses → T1071.003

**Source object:** [[01 ATT&CK/S0022 - Uroburos|S0022: Uroburos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.003 - Mail Protocols|T1071.003: Mail Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Uroburos](https://attack.mitre.org/software/S0022) can use custom communications protocols that ride over SMTP.(Citation: Joint Cybersecurity Advisory AA23-129A Snake Malware May 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ce884c7-71c5-4f46-b09c-1abb45d8341b`.
