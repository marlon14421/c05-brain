---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1053.003"
stix_relationship_id: "relationship--06287ae2-325c-448e-8790-3c37492e1c29"
---
# Relationship 1250: M1047 — mitigates → T1053.003

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1053.003 - Cron|T1053.003: Cron]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Review changes to the cron schedule. cron execution can be reviewed within the /var/log directory. To validate the location of the cron log file, check the syslog config at /etc/rsyslog.conf or /etc/syslog.conf .

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--06287ae2-325c-448e-8790-3c37492e1c29`.
