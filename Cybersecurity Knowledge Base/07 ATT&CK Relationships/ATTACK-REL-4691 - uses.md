---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1091"
target_object: "T1619"
stix_relationship_id: "relationship--64d9fee3-d0c8-40e5-b295-d43ec719bb81"
---
# Relationship 4691: S1091 — uses → T1619

**Source object:** [[01 ATT&CK/S1091 - Pacu|S1091: Pacu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1619 - Cloud Storage Object Discovery|T1619: Cloud Storage Object Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pacu](https://attack.mitre.org/software/S1091) can enumerate AWS storage services, such as S3 buckets and Elastic Block Store volumes.(Citation: GitHub Pacu)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--64d9fee3-d0c8-40e5-b295-d43ec719bb81`.
