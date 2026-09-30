---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "T1059.003"
stix_relationship_id: "relationship--81a15403-9bb3-408a-8da6-97c64209c829"
---
# Relationship 7853: G0096 — uses → T1059.003

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT41](https://attack.mitre.org/groups/G0096) used cmd.exe /c to execute commands on remote machines.(Citation: FireEye APT41 Aug 2019) [APT41](https://attack.mitre.org/groups/G0096) used a batch file to install persistence for the [Cobalt Strike](https://attack.mitre.org/software/S0154) BEACON loader.(Citation: FireEye APT41 March 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81a15403-9bb3-408a-8da6-97c64209c829`.
