---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0058"
target_object: "T1056.001"
stix_relationship_id: "relationship--8d4effdd-6d91-473d-aa81-d121f1c77881"
---
# Relationship 5850: S0058 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0058 - SslMM|S0058: SslMM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SslMM](https://attack.mitre.org/software/S0058) creates a new thread implementing a keylogging facility using Windows Keyboard Accelerators.(Citation: Baumgartner Naikon 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8d4effdd-6d91-473d-aa81-d121f1c77881`.
