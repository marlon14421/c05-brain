---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0622"
target_object: "T1056.001"
stix_relationship_id: "relationship--5903c147-70f5-45fe-a63c-418c61566422"
---
# Relationship 9891: S0622 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0622 - AppleSeed|S0622: AppleSeed]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AppleSeed](https://attack.mitre.org/software/S0622) can use GetKeyState and GetKeyboardState to capture keystrokes on the victim’s machine.(Citation: Malwarebytes Kimsuky June 2021)(Citation: KISA Operation Muzabi)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5903c147-70f5-45fe-a63c-418c61566422`.
