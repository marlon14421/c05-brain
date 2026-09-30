---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1078.003"
stix_relationship_id: "relationship--4f8dca9b-86d0-4d97-98ed-c98240cc3933"
---
# Relationship 0625: M1026 — mitigates → T1078.003

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1078.003 - Local Accounts|T1078.003: Local Accounts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Audit local accounts permission levels routinely to look for situations that could allow an adversary to gain wide access by obtaining credentials of a privileged account. (Citation: TechNet Credential Theft) (Citation: TechNet Least Privilege) Limit the usage of local administrator accounts to be used for day-to-day operations that may expose them to potential adversaries. For example, audit the use of service accounts in Kubernetes, and avoid automatically granting them access to the Kubernetes API if this is not required.(Citation: Kubernetes Service Accounts) Implementing LAPS may also help prevent reuse of local administrator credentials across a domain.(Citation: Microsoft Remote Use of Local)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f8dca9b-86d0-4d97-98ed-c98240cc3933`.
