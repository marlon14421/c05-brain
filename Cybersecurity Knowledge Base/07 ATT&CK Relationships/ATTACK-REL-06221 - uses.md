---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1078"
target_object: "T1082"
stix_relationship_id: "relationship--87ef3b62-acb4-4cd2-86ec-36683a57bedf"
---
# Relationship 6221: S1078 — uses → T1082

**Source object:** [[01 ATT&CK/S1078 - RotaJakiro|S1078: RotaJakiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RotaJakiro](https://attack.mitre.org/software/S1078) executes a set of commands to collect device information, including `uname`. Another example is the `cat /etc/*release | uniq` command used to collect the current OS distribution.(Citation: RotaJakiro 2021 netlab360 analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87ef3b62-acb4-4cd2-86ec-36683a57bedf`.
