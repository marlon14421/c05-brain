---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0268"
target_object: "T1218.011"
stix_relationship_id: "relationship--9088b52e-8e07-4fd4-ac80-66df7f877adf"
---
# Relationship 3793: S0268 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0268 - Bisonal|S0268: Bisonal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bisonal](https://attack.mitre.org/software/S0268) has used rundll32.exe to execute as part of the Registry Run key it adds: HKEY_CURRENT_USER \Software\Microsoft\Windows\CurrentVersion\Run\”vert” = “rundll32.exe c:\windows\temp\pvcu.dll , Qszdez” .(Citation: Unit 42 Bisonal July 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9088b52e-8e07-4fd4-ac80-66df7f877adf`.
