---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1564.002"
stix_relationship_id: "relationship--a45378ad-7f38-47d3-87e1-a3133b29b89b"
---
# Relationship 1027: M1028 — mitigates → T1564.002

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1564.002 - Hidden Users|T1564.002: Hidden Users]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

If the computer is domain joined, then group policy can help restrict the ability to create or hide users. Similarly, preventing the modification of the /Library/Preferences/com.apple.loginwindow Hide500Users value will force all users to be visible.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a45378ad-7f38-47d3-87e1-a3133b29b89b`.
