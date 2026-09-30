---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9044"
target_object: "T1683.001"
stix_relationship_id: "relationship--33be09de-5a52-4388-9861-49d5fc05f638"
---
# Relationship 4133: S9044 — uses → T1683.001

**Source object:** [[01 ATT&CK/S9044 - Kali365|S9044: Kali365]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1683.001 - Written Content|T1683.001: Written Content]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kali365](https://attack.mitre.org/software/S9044) has generated tailored branded phishing lures to target victims utilizing a myriad of reputable services and brands that entice users to interact with the content.(Citation: Artic Wolf Labs Kali365 Device Code April 2026)(Citation: Artic Wolf Kali365 Device Code OAuth June 2026)(Citation: FBI IC3 Alert I-052126 Kali365 May 2026)(Citation: Huntress Kali365 Device Code June 2026) [Kali365](https://attack.mitre.org/software/S9044) has also been enabled with AI such as Claude Sonnet that evaluates emails and generates tailored responses to facilitate BEC activities.(Citation: Huntress Kali365 Device Code June 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--33be09de-5a52-4388-9861-49d5fc05f638`.
