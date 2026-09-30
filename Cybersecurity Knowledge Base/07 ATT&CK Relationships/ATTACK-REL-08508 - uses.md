---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9034"
target_object: "T1480"
stix_relationship_id: "relationship--0e7e92e6-2163-44cb-b8c5-420577aeada7"
---
# Relationship 8508: S9034 — uses → T1480

**Source object:** [[01 ATT&CK/S9034 - Tsundere Botnet|S9034: Tsundere Botnet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tsundere Botnet](https://attack.mitre.org/software/S9034) has checked the victim machine’s location to avoid infecting in the Commonwealth of Independent States (CIS) region.(Citation: SecureListUbiedo_Tsundere_Nov2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0e7e92e6-2163-44cb-b8c5-420577aeada7`.
