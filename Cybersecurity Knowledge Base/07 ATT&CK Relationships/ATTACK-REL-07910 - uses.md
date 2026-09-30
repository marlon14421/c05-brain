---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0631"
target_object: "T1036.005"
stix_relationship_id: "relationship--91668436-9db8-4a88-9dc0-c55681f80a6f"
---
# Relationship 7910: S0631 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0631 - Chaes|S0631: Chaes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chaes](https://attack.mitre.org/software/S0631) has used an unsigned, crafted DLL module named hha.dll that was designed to look like a legitimate 32-bit Windows DLL.(Citation: Cybereason Chaes Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91668436-9db8-4a88-9dc0-c55681f80a6f`.
