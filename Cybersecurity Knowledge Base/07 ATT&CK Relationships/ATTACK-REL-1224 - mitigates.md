---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1552"
stix_relationship_id: "relationship--5401a61d-a795-4619-aa7e-fdf54cd4358e"
---
# Relationship 1224: M1028 — mitigates → T1552

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1552 - Unsecured Credentials|T1552: Unsecured Credentials]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

There are multiple methods of preventing a user's command history from being flushed to their .bash_history file, including use of the following commands: set +o history and set -o history to start logging again; unset HISTFILE being added to a user's .bash_rc file; and ln -s /dev/null ~/.bash_history to write commands to /dev/null instead.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5401a61d-a795-4619-aa7e-fdf54cd4358e`.
