---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1233"
target_object: "T1553.002"
stix_relationship_id: "relationship--8ffa65ef-05b7-49bb-ba1e-bbf5d1dc5857"
---
# Relationship 4961: S1233 — uses → T1553.002

**Source object:** [[01 ATT&CK/S1233 - PAKLOG|S1233: PAKLOG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PAKLOG](https://attack.mitre.org/software/S1233) has used legitimate signed binaries such as PACLOUD.exe for follow-on execution of malicious DLLs through DLL Side-Loading.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ffa65ef-05b7-49bb-ba1e-bbf5d1dc5857`.
