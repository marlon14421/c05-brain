---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1059.008"
stix_relationship_id: "relationship--f63970b4-a3fd-4fc9-8685-2baf0ff6ffff"
---
# Relationship 0245: M1018 — mitigates → T1059.008

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1059.008 - Network Device CLI|T1059.008: Network Device CLI]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use of Authentication, Authorization, and Accounting (AAA) systems will limit actions users can perform and provide a history of user actions to detect unauthorized use and abuse. Ensure least privilege principles are applied to user accounts and groups so that only authorized users can perform configuration changes. (Citation: Cisco IOS Software Integrity Assurance - AAA)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f63970b4-a3fd-4fc9-8685-2baf0ff6ffff`.
