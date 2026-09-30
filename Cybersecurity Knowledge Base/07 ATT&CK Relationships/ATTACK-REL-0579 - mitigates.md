---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1022"
target_object: "T1543.002"
stix_relationship_id: "relationship--9d7f9d7b-c246-4849-b65e-1ac45208b427"
---
# Relationship 0579: M1022 — mitigates → T1543.002

**Source object:** [[01 ATT&CK/M1022 - Restrict File and Directory Permissions|M1022: Restrict File and Directory Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1543.002 - Systemd Service|T1543.002: Systemd Service]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Restrict read/write access to systemd unit files to only select privileged users who have a legitimate need to manage system services.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d7f9d7b-c246-4849-b65e-1ac45208b427`.
