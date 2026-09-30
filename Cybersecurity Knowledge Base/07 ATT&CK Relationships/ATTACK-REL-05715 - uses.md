---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9015"
target_object: "T1574.007"
stix_relationship_id: "relationship--5b6d5eef-dc61-4e43-a1da-f0967f77afdd"
---
# Relationship 5715: S9015 — uses → T1574.007

**Source object:** [[01 ATT&CK/S9015 - BRICKSTORM|S9015: BRICKSTORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.007 - Path Interception by PATH Environment Variable|T1574.007: Path Interception by PATH Environment Variable]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BRICKSTORM](https://attack.mitre.org/software/S9015) has checked hard-coded paths of `/etc/sysconfig/` or `/etc/sysconfig/network` prior to execution and loading file contents from that path.(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b6d5eef-dc61-4e43-a1da-f0967f77afdd`.
