---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0177"
target_object: "T1055.011"
stix_relationship_id: "relationship--c56de8bc-ad9e-415a-8840-ae294ed4f88a"
---
# Relationship 3403: S0177 — uses → T1055.011

**Source object:** [[01 ATT&CK/S0177 - Power Loader|S0177: Power Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.011 - Extra Window Memory Injection|T1055.011: Extra Window Memory Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Power Loader](https://attack.mitre.org/software/S0177) overwrites Explorer’s Shell_TrayWnd extra window memory to redirect execution to a NTDLL function that is abused to assemble and execute a return-oriented programming (ROP) chain and create a malicious thread within Explorer.exe.(Citation: MalwareTech Power Loader Aug 2013)(Citation: WeLiveSecurity Gapz and Redyms Mar 2013)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c56de8bc-ad9e-415a-8840-ae294ed4f88a`.
