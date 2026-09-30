---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0362"
target_object: "T1110.003"
stix_relationship_id: "relationship--1cf57140-fe45-4c26-8946-071252ae8276"
---
# Relationship 5328: S0362 — uses → T1110.003

**Source object:** [[01 ATT&CK/S0362 - Linux Rabbit|S0362: Linux Rabbit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110.003 - Password Spraying|T1110.003: Password Spraying]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Linux Rabbit](https://attack.mitre.org/software/S0362) brute forces SSH passwords in order to attempt to gain access and install its malware onto the server. (Citation: Anomali Linux Rabbit 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1cf57140-fe45-4c26-8946-071252ae8276`.
