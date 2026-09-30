---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1053.003"
stix_relationship_id: "relationship--be61d80d-2291-4572-960c-dd741534f855"
---
# Relationship 1045: M1018 — mitigates → T1053.003

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1053.003 - Cron|T1053.003: Cron]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

cron permissions are controlled by /etc/cron.allow and /etc/cron.deny . If there is a cron.allow file, then the user or users that need to use cron will need to be listed in the file. cron.deny is used to explicitly disallow users from using cron. If neither files exist, then only the super user is allowed to run cron.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be61d80d-2291-4572-960c-dd741534f855`.
