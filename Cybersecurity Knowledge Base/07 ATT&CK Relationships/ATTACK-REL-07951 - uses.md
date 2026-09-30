---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0416"
target_object: "T1056.004"
stix_relationship_id: "relationship--71a3a771-3674-4b44-8742-bed627f178b3"
---
# Relationship 7951: S0416 — uses → T1056.004

**Source object:** [[01 ATT&CK/S0416 - RDFSNIFFER|S0416: RDFSNIFFER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.004 - Credential API Hooking|T1056.004: Credential API Hooking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RDFSNIFFER](https://attack.mitre.org/software/S0416) hooks several Win32 API functions to hijack elements of the remote system management user-interface.(Citation: FireEye FIN7 Oct 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71a3a771-3674-4b44-8742-bed627f178b3`.
