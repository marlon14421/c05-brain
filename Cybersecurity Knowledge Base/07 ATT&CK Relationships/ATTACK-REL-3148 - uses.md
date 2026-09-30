---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0367"
target_object: "T1547.001"
stix_relationship_id: "relationship--3236ca50-2342-455a-b258-6a085cae8fc2"
---
# Relationship 3148: S0367 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0367 - Emotet|S0367: Emotet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Emotet](https://attack.mitre.org/software/S0367) has been observed adding the downloaded payload to the HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run key to maintain persistence.(Citation: Symantec Emotet Jul 2018)(Citation: US-CERT Emotet Jul 2018)(Citation: Picus Emotet Dec 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3236ca50-2342-455a-b258-6a085cae8fc2`.
