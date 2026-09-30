---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1207"
target_object: "T1566.001"
stix_relationship_id: "relationship--97d36a97-c49f-4706-8597-3d9dd86d8c60"
---
# Relationship 4265: S1207 — uses → T1566.001

**Source object:** [[01 ATT&CK/S1207 - XLoader|S1207: XLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[XLoader](https://attack.mitre.org/software/S1207) has been delivered as a phishing attachment, including PDFs with embedded links, Word and Excel files, and various archive files (ZIP, RAR, ACE, and ISOs) containing EXE payloads.(Citation: Google XLoader 2017)(Citation: Acronis XLoader 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--97d36a97-c49f-4706-8597-3d9dd86d8c60`.
