---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1001.003"
stix_relationship_id: "relationship--5025e4e1-4862-430c-a5fd-8ca7fece809b"
---
# Relationship 8039: G0129 — uses → T1001.003

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.003 - Protocol or Service Impersonation|T1001.003: Protocol or Service Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has utilized TLS record headers in network packets to impersonate various versions of TLS protocols to blend in with legitimate network traffic. [Mustang Panda](https://attack.mitre.org/groups/G0129) has used FakeTLS to communicate with its C2 servers.(Citation: Zscaler)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5025e4e1-4862-430c-a5fd-8ca7fece809b`.
