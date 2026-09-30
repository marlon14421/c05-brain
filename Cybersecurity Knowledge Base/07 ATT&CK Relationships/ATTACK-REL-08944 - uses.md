---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1035"
target_object: "T1132.002"
stix_relationship_id: "relationship--361df799-64ee-405f-bd31-788ecc5c8d45"
---
# Relationship 8944: S1035 — uses → T1132.002

**Source object:** [[01 ATT&CK/S1035 - Small Sieve|S1035: Small Sieve]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.002 - Non-Standard Encoding|T1132.002: Non-Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Small Sieve](https://attack.mitre.org/software/S1035) can use a custom hex byte swapping encoding scheme to obfuscate tasking traffic.(Citation: DHS CISA AA22-055A MuddyWater February 2022)(Citation: NCSC GCHQ Small Sieve Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--361df799-64ee-405f-bd31-788ecc5c8d45`.
