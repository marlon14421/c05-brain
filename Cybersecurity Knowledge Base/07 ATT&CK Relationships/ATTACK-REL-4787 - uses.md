---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0022"
target_object: "T1083"
stix_relationship_id: "relationship--fc825f8c-ee7a-4b03-9d67-cd736d61b893"
---
# Relationship 4787: S0022 — uses → T1083

**Source object:** [[01 ATT&CK/S0022 - Uroburos|S0022: Uroburos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Uroburos](https://attack.mitre.org/software/S0022) can search for specific files on a compromised system.(Citation: Joint Cybersecurity Advisory AA23-129A Snake Malware May 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc825f8c-ee7a-4b03-9d67-cd736d61b893`.
