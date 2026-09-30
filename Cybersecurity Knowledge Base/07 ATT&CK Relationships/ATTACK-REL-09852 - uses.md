---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0082"
target_object: "T1027.001"
stix_relationship_id: "relationship--d200ba08-8179-495e-a854-9b13be5c0f93"
---
# Relationship 9852: S0082 — uses → T1027.001

**Source object:** [[01 ATT&CK/S0082 - Emissary|S0082: Emissary]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.001 - Binary Padding|T1027.001: Binary Padding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A variant of [Emissary](https://attack.mitre.org/software/S0082) appends junk data to the end of its DLL file to create a large file that may exceed the maximum size that anti-virus programs can scan.(Citation: Emissary Trojan Feb 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d200ba08-8179-495e-a854-9b13be5c0f93`.
