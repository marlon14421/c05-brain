---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0038"
target_object: "T1573.001"
stix_relationship_id: "relationship--7cb48d6d-1171-4e9d-87c7-4779293f6921"
---
# Relationship 2841: S0038 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0038 - Duqu|S0038: Duqu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [Duqu](https://attack.mitre.org/software/S0038) command and control protocol's data stream can be encrypted with AES-CBC.(Citation: Symantec W32.Duqu)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7cb48d6d-1171-4e9d-87c7-4779293f6921`.
