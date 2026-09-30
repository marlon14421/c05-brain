---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1134.001"
stix_relationship_id: "relationship--b719d37b-8f0e-4704-b21d-8977a5c7cceb"
---
# Relationship 4413: G0007 — uses → T1134.001

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.001 - Token Impersonation-Theft|T1134.001: Token Impersonation/Theft]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has used CVE-2015-1701 to access the SYSTEM token and copy it into the current process as part of privilege escalation.(Citation: FireEye Op RussianDoll)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b719d37b-8f0e-4704-b21d-8977a5c7cceb`.
