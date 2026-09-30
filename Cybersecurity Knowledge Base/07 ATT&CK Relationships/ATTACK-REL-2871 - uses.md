---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0055"
target_object: "T1589.002"
stix_relationship_id: "relationship--4a6baa9b-c919-421b-8684-0ba7953bd8df"
---
# Relationship 2871: C0055 — uses → T1589.002

**Source object:** [[01 ATT&CK/C0055 - Quad7 Activity|C0055: Quad7 Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1589.002 - Email Addresses|T1589.002: Email Addresses]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Quad7 Activity](https://attack.mitre.org/campaigns/C0055) has gathered targeted individual’s e-mail addresses for the password spraying attempts.(Citation: Medium 777-Botnet)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4a6baa9b-c919-421b-8684-0ba7953bd8df`.
