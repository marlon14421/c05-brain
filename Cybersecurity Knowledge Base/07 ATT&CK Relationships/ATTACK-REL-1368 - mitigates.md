---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1035"
target_object: "T1612"
stix_relationship_id: "relationship--1720444b-e442-423e-ba6f-48079ad8b04e"
---
# Relationship 1368: M1035 — mitigates → T1612

**Source object:** [[01 ATT&CK/M1035 - Limit Access to Resource Over Network|M1035: Limit Access to Resource Over Network]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1612 - Build Image on Host|T1612: Build Image on Host]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit communications with the container service to local Unix sockets or remote access via SSH. Require secure port access to communicate with the APIs over TLS by disabling unauthenticated access to the Docker API on port 2375. Instead, communicate with the Docker API over TLS on port 2376.(Citation: Docker Daemon Socket Protect)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1720444b-e442-423e-ba6f-48079ad8b04e`.
