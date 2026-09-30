---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0017"
target_object: "T1048.003"
stix_relationship_id: "relationship--6c10da0b-4dfd-4389-b3e3-3599a2fab859"
---
# Relationship 7038: C0017 — uses → T1048.003

**Source object:** [[01 ATT&CK/C0017 - C0017|C0017: C0017]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048.003 - Exfiltration Over Unencrypted Non-C2 Protocol|T1048.003: Exfiltration Over Unencrypted Non-C2 Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0017](https://attack.mitre.org/campaigns/C0017), [APT41](https://attack.mitre.org/groups/G0096) exfiltrated victim data via DNS lookups by encoding and prepending it as subdomains to the attacker-controlled domain.(Citation: Mandiant APT41)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c10da0b-4dfd-4389-b3e3-3599a2fab859`.
