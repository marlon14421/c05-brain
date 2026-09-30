---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0483"
target_object: "T1071.001"
stix_relationship_id: "relationship--b82ab6ba-b590-440d-bfd1-75f18560a8b4"
---
# Relationship 6080: S0483 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0483 - IcedID|S0483: IcedID]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IcedID](https://attack.mitre.org/software/S0483) has used HTTPS in communications with C2.(Citation: Juniper IcedID June 2020)(Citation: DFIR_Quantum_Ransomware)(Citation: DFIR_Sodinokibi_Ransomware)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b82ab6ba-b590-440d-bfd1-75f18560a8b4`.
