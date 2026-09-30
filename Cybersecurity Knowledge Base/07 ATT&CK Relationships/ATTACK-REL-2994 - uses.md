---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1021.007"
stix_relationship_id: "relationship--93e345d9-a7d2-4abd-be34-46211fa64a7d"
---
# Relationship 2994: G0016 — uses → T1021.007

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.007 - Cloud Services|T1021.007: Cloud Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) has leveraged compromised high-privileged on-premises accounts synced to Office 365 to move laterally into a cloud environment, including through the use of Azure AD PowerShell.(Citation: Mandiant Remediation and Hardening Strategies for Microsoft 365)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--93e345d9-a7d2-4abd-be34-46211fa64a7d`.
