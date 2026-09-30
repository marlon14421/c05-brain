---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0661"
target_object: "T1040"
stix_relationship_id: "relationship--98b8b974-ac4f-4286-b657-f34f813c1d12"
---
# Relationship 6988: S0661 — uses → T1040

**Source object:** [[01 ATT&CK/S0661 - FoggyWeb|S0661: FoggyWeb]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FoggyWeb](https://attack.mitre.org/software/S0661) can configure custom listeners to passively monitor all incoming HTTP GET and POST requests sent to the AD FS server from the intranet/internet and intercept HTTP requests that match the custom URI patterns defined by the actor.(Citation: MSTIC FoggyWeb September 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--98b8b974-ac4f-4286-b657-f34f813c1d12`.
