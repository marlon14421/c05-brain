---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1053"
target_object: "T1530"
stix_relationship_id: "relationship--35589283-3028-444b-94d1-9b64ae6d8487"
---
# Relationship 3278: G1053 — uses → T1530

**Source object:** [[01 ATT&CK/G1053 - Storm-0501|G1053: Storm-0501]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1530 - Data from Cloud Storage|T1530: Data from Cloud Storage]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Storm-0501](https://attack.mitre.org/groups/G1053) had modified Azure Storage account resources through the `Microsoft.Storage/storageAccounts/write` operation to expose non-remotely accessible accounts for data exfiltration.(Citation: Microsoft Storm-0501 Embargo Ransomware August 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--35589283-3028-444b-94d1-9b64ae6d8487`.
