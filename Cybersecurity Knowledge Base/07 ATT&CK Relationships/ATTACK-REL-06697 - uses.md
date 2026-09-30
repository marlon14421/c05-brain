---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0412"
target_object: "T1059.003"
stix_relationship_id: "relationship--a322b9a0-57f8-4eda-a6f4-2adbc1376bfb"
---
# Relationship 6697: S0412 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0412 - ZxShell|S0412: ZxShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZxShell](https://attack.mitre.org/software/S0412) can launch a reverse command shell.(Citation: FireEye APT41 Aug 2019)(Citation: Talos ZxShell Oct 2014)(Citation: Secureworks BRONZEUNION Feb 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a322b9a0-57f8-4eda-a6f4-2adbc1376bfb`.
