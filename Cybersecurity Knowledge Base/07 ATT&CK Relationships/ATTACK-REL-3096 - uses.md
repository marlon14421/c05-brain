---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0373"
target_object: "T1566.001"
stix_relationship_id: "relationship--6d1cd674-0466-4209-b9b5-7ce45ed359d1"
---
# Relationship 3096: S0373 — uses → T1566.001

**Source object:** [[01 ATT&CK/S0373 - Astaroth|S0373: Astaroth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Astaroth](https://attack.mitre.org/software/S0373) has been delivered via malicious e-mail attachments.(Citation: Securelist Brazilian Banking Malware July 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6d1cd674-0466-4209-b9b5-7ce45ed359d1`.
