---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9003"
target_object: "T1059.007"
stix_relationship_id: "relationship--1e95c694-902e-4d6c-b5bd-17888e426d55"
---
# Relationship 3436: S9003 — uses → T1059.007

**Source object:** [[01 ATT&CK/S9003 - evilginx2|S9003: evilginx2]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[evilginx2](https://attack.mitre.org/software/S9003) can inject JavaScript code into HTML content to customize phishing attacks.(Citation: Breakdev Evilginx 2.3 JAN 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1e95c694-902e-4d6c-b5bd-17888e426d55`.
