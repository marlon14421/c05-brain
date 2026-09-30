---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0527"
target_object: "T1204.002"
stix_relationship_id: "relationship--63e937c3-f395-4146-8061-6c00550bcd6a"
---
# Relationship 4562: S0527 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0527 - CSPY Downloader|S0527: CSPY Downloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CSPY Downloader](https://attack.mitre.org/software/S0527) has been delivered via malicious documents with embedded macros.(Citation: Cybereason Kimsuky November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--63e937c3-f395-4146-8061-6c00550bcd6a`.
