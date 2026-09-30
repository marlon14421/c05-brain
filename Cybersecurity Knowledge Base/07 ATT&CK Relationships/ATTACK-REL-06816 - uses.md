---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0143"
target_object: "T1036.010"
stix_relationship_id: "relationship--3cd7c6ee-2972-4f21-a0cc-ccb70cb5cf23"
---
# Relationship 6816: S0143 — uses → T1036.010

**Source object:** [[01 ATT&CK/S0143 - Flame|S0143: Flame]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.010 - Masquerade Account Name|T1036.010: Masquerade Account Name]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Flame](https://attack.mitre.org/software/S0143) can create backdoor accounts with login `HelpAssistant` on domain connected systems if appropriate rights are available.(Citation: Kaspersky Flame)(Citation: Kaspersky Flame Functionality)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3cd7c6ee-2972-4f21-a0cc-ccb70cb5cf23`.
