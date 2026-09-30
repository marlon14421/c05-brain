---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1558"
stix_relationship_id: "relationship--fbba8143-52be-4b81-8af7-94518799faaa"
---
# Relationship 0905: M1026 — mitigates → T1558

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1558 - Steal or Forge Kerberos Tickets|T1558: Steal or Forge Kerberos Tickets]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit domain admin account permissions to domain controllers and limited servers. Delegate other admin functions to separate accounts. Limit service accounts to minimal required privileges, including membership in privileged groups such as Domain Administrators.(Citation: AdSecurity Cracking Kerberos Dec 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fbba8143-52be-4b81-8af7-94518799faaa`.
