---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1161"
target_object: "T1686"
stix_relationship_id: "relationship--ad269937-6339-4686-8f3b-369e0c65afc6"
---
# Relationship 6645: S1161 — uses → T1686

**Source object:** [[01 ATT&CK/S1161 - BPFDoor|S1161: BPFDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1686 - Disable or Modify System Firewall|T1686: Disable or Modify System Firewall]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BPFDoor](https://attack.mitre.org/software/S1161) starts a shell on a high TCP port starting at 42391 up to 43391, then changes the local `iptables` rules to redirect all packets from the attacker to the shell port.(Citation: Sandfly BPFDoor 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ad269937-6339-4686-8f3b-369e0c65afc6`.
