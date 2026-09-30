---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0238"
target_object: "T1119"
stix_relationship_id: "relationship--4ed42682-d3ad-4a4f-8576-ccdf28ce642b"
---
# Relationship 9268: S0238 — uses → T1119

**Source object:** [[01 ATT&CK/S0238 - Proxysvc|S0238: Proxysvc]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Proxysvc](https://attack.mitre.org/software/S0238) automatically collects data about the victim and sends it to the control server.(Citation: McAfee GhostSecret)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4ed42682-d3ad-4a4f-8576-ccdf28ce642b`.
