---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1558.005"
stix_relationship_id: "relationship--67413fb8-ef1c-4ba7-b60b-fd7ad75f8a69"
---
# Relationship 0805: M1047 — mitigates → T1558.005

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1558.005 - Ccache Files|T1558.005: Ccache Files]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enable and perform audits or scans of systems, permissions, insecure software, insecure configurations, etc. to identify potential weaknesses.(Citation: Brining MimiKatz to Unix) For example, use auditd to audit access to hashes, machine tickets, or /tmp files. If using sssd and Vintela, ensure kerberos is disabled if not being used.(Citation: audits linikatz)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--67413fb8-ef1c-4ba7-b60b-fd7ad75f8a69`.
