---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1574.006"
stix_relationship_id: "relationship--086ec3ab-803e-4531-a451-15fa9f06297c"
---
# Relationship 0018: M1028 — mitigates → T1574.006

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1574.006 - Dynamic Linker Hijacking|T1574.006: Dynamic Linker Hijacking]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

When System Integrity Protection (SIP) is enabled in macOS, the aforementioned environment variables are ignored when executing protected binaries. Third-party applications can also leverage Apple’s Hardened Runtime, ensuring these environment variables are subject to imposed restrictions.(Citation: Apple Developer Doco Hardened Runtime) Admins can add restrictions to applications by setting the setuid and/or setgid bits, use entitlements, or have a __RESTRICT segment in the Mach-O binary.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--086ec3ab-803e-4531-a451-15fa9f06297c`.
