---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1037"
target_object: "T1071.003"
stix_relationship_id: "relationship--4e7668ba-bde1-412c-b22d-65b57baabd0d"
---
# Relationship 1060: M1037 — mitigates → T1071.003

**Source object:** [[01 ATT&CK/M1037 - Filter Network Traffic|M1037: Filter Network Traffic]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1071.003 - Mail Protocols|T1071.003: Mail Protocols]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit the ability of servers and critical systems to initiate outbound email communications. Filtering SMTP/IMAP/POP3 traffic to only trusted mail servers reduces the risk of attackers using compromised systems to exfiltrate data via email or to receive commands from attacker-controlled email accounts.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e7668ba-bde1-412c-b22d-65b57baabd0d`.
