---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0335"
target_object: "T1140"
stix_relationship_id: "relationship--848313af-f9c3-4b51-a24a-d2e88487ab53"
---
# Relationship 5628: S0335 — uses → T1140

**Source object:** [[01 ATT&CK/S0335 - Carbon|S0335: Carbon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carbon](https://attack.mitre.org/software/S0335) decrypts task and configuration files for execution.(Citation: ESET Carbon Mar 2017)(Citation: Accenture HyperStack October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--848313af-f9c3-4b51-a24a-d2e88487ab53`.
