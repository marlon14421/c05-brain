---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0056"
target_object: "T1205.001"
stix_relationship_id: "relationship--b92d6b45-e211-4168-ac32-80427bf1b9d2"
---
# Relationship 8481: G0056 — uses → T1205.001

**Source object:** [[01 ATT&CK/G0056 - PROMETHIUM|G0056: PROMETHIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205.001 - Port Knocking|T1205.001: Port Knocking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PROMETHIUM](https://attack.mitre.org/groups/G0056) has used a script that configures the knockd service and firewall to only accept C2 connections from systems that use a specified sequence of knock ports.(Citation: Bitdefender StrongPity June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b92d6b45-e211-4168-ac32-80427bf1b9d2`.
