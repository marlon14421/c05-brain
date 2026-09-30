---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1240"
target_object: "T1497"
stix_relationship_id: "relationship--c398b815-5ec1-45a9-bbe8-14153ae5d703"
---
# Relationship 6700: S1240 — uses → T1497

**Source object:** [[01 ATT&CK/S1240 - RedLine Stealer|S1240: RedLine Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497 - Virtualization-Sandbox Evasion|T1497: Virtualization/Sandbox Evasion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedLine Stealer](https://attack.mitre.org/software/S1240) has an anti-sandbox technique that requires the malware to consistently check with the C2 server, if the communication fails [RedLine Stealer](https://attack.mitre.org/software/S1240) will not continue execution.(Citation: Splunk RedLine Stealer June 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c398b815-5ec1-45a9-bbe8-14153ae5d703`.
