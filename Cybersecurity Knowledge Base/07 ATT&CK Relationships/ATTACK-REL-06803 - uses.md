---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0386"
target_object: "T1056.004"
stix_relationship_id: "relationship--3c7ad637-8d4e-4baa-9cd9-7655d29e1e28"
---
# Relationship 6803: S0386 — uses → T1056.004

**Source object:** [[01 ATT&CK/S0386 - Ursnif|S0386: Ursnif]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.004 - Credential API Hooking|T1056.004: Credential API Hooking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ursnif](https://attack.mitre.org/software/S0386) has hooked APIs to perform a wide variety of information theft, such as monitoring traffic from browsers.(Citation: TrendMicro Ursnif Mar 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c7ad637-8d4e-4baa-9cd9-7655d29e1e28`.
