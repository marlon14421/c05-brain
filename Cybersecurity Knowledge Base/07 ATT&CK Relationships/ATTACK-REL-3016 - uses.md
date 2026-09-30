---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0062"
target_object: "T1566.001"
stix_relationship_id: "relationship--76021528-7cb6-461a-870a-f681cac19285"
---
# Relationship 3016: G0062 — uses → T1566.001

**Source object:** [[01 ATT&CK/G0062 - TA459|G0062: TA459]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA459](https://attack.mitre.org/groups/G0062) has targeted victims using spearphishing emails with malicious Microsoft Word attachments.(Citation: Proofpoint TA459 April 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76021528-7cb6-461a-870a-f681cac19285`.
