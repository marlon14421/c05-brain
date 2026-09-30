---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1210"
stix_relationship_id: "relationship--a358f0a9-b5b9-4a84-8c83-dc0a1325d63e"
---
# Relationship 5385: G0007 — uses → T1210

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1210 - Exploitation of Remote Services|T1210: Exploitation of Remote Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) exploited a Windows SMB Remote Code Execution Vulnerability to conduct lateral movement.(Citation: FireEye APT28)(Citation: FireEye APT28 Hospitality Aug 2017)(Citation: MS17-010 March 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a358f0a9-b5b9-4a84-8c83-dc0a1325d63e`.
