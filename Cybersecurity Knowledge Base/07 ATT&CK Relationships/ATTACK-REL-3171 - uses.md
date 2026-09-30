---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0039"
target_object: "T1056"
stix_relationship_id: "relationship--a3a64ecb-572b-4dc3-b95f-8b46be7b857a"
---
# Relationship 3171: C0039 — uses → T1056

**Source object:** [[01 ATT&CK/C0039 - Versa Director Zero Day Exploitation|C0039: Versa Director Zero Day Exploitation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056 - Input Capture|T1056: Input Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Versa Director Zero Day Exploitation](https://attack.mitre.org/campaigns/C0039) intercepted and harvested credentials from user logins to compromised devices.(Citation: Lumen Versa 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3a64ecb-572b-4dc3-b95f-8b46be7b857a`.
