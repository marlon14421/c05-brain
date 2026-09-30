---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1242"
target_object: "T1570"
stix_relationship_id: "relationship--731fd895-2b35-4ac4-a16c-f85340543595"
---
# Relationship 4202: S1242 — uses → T1570

**Source object:** [[01 ATT&CK/S1242 - Qilin|S1242: Qilin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1570 - Lateral Tool Transfer|T1570: Lateral Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Qilin](https://attack.mitre.org/software/S1242) has used [PsExec](https://attack.mitre.org/software/S0029) to distribute a second encryptor, named encryptor_1.exe, across the targeted environment.(Citation: Cisco Talos Qilin Ransomware OCT 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--731fd895-2b35-4ac4-a16c-f85340543595`.
