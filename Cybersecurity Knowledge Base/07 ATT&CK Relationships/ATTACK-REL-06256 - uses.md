---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0374"
target_object: "T1053.003"
stix_relationship_id: "relationship--15e5ddeb-ad28-44c0-a7a7-0fe69e05456d"
---
# Relationship 6256: S0374 — uses → T1053.003

**Source object:** [[01 ATT&CK/S0374 - SpeakUp|S0374: SpeakUp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.003 - Cron|T1053.003: Cron]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SpeakUp](https://attack.mitre.org/software/S0374) uses cron tasks to ensure persistence. (Citation: CheckPoint SpeakUp Feb 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15e5ddeb-ad28-44c0-a7a7-0fe69e05456d`.
