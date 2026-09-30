---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1032"
target_object: "T1078.003"
stix_relationship_id: "relationship--528d581d-aa34-4162-a773-6b329c3af4cb"
---
# Relationship 1169: M1032 — mitigates → T1078.003

**Source object:** [[01 ATT&CK/M1032 - Multi-factor Authentication|M1032: Multi-factor Authentication]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1078.003 - Local Accounts|T1078.003: Local Accounts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enable multi-factor authentication (MFA) for local accounts to add an extra layer of protection against credential theft and misuse. MFA can be implemented using methods like mobile-based authenticators or hardware tokens, even in environments that do not rely on domain controllers or cloud services. This additional security measure can help reduce the risk of adversaries gaining unauthorized access to local systems and resources.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--528d581d-aa34-4162-a773-6b329c3af4cb`.
