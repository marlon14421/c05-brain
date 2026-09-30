---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0048"
target_object: "T1003"
stix_relationship_id: "relationship--2e80a049-220e-4d47-98f7-c0dbfe245cdc"
---
# Relationship 5325: S0048 — uses → T1003

**Source object:** [[01 ATT&CK/S0048 - PinchDuke|S0048: PinchDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003 - OS Credential Dumping|T1003: OS Credential Dumping]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PinchDuke](https://attack.mitre.org/software/S0048) steals credentials from compromised hosts. [PinchDuke](https://attack.mitre.org/software/S0048)'s credential stealing functionality is believed to be based on the source code of the Pinch credential stealing malware (also known as LdPinch). Credentials targeted by [PinchDuke](https://attack.mitre.org/software/S0048) include ones associated many sources such as WinInet Credential Cache, and Lightweight Directory Access Protocol (LDAP).(Citation: F-Secure The Dukes)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e80a049-220e-4d47-98f7-c0dbfe245cdc`.
