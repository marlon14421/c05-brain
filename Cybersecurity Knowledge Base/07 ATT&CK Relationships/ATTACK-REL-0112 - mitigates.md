---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1042"
target_object: "T1098.004"
stix_relationship_id: "relationship--8faa230d-ced2-4289-81c5-554fd6dc62fd"
---
# Relationship 0112: M1042 — mitigates → T1098.004

**Source object:** [[01 ATT&CK/M1042 - Disable or Remove Feature or Program|M1042: Disable or Remove Feature or Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1098.004 - SSH Authorized Keys|T1098.004: SSH Authorized Keys]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Disable SSH if it is not necessary on a host or restrict SSH access for specific users/groups using /etc/ssh/sshd_config . Setting the `PermitRootLogin` directive to `no` will prevent the root user from logging in via SSH.(Citation: Broadcom ESXi SSH)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8faa230d-ced2-4289-81c5-554fd6dc62fd`.
