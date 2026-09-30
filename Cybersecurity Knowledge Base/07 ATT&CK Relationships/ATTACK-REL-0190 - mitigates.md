---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1015"
target_object: "T1550.003"
stix_relationship_id: "relationship--918a7d67-faea-4a41-9ed3-e3558fca73db"
---
# Relationship 0190: M1015 — mitigates → T1550.003

**Source object:** [[01 ATT&CK/M1015 - Active Directory Configuration|M1015: Active Directory Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1550.003 - Pass the Ticket|T1550.003: Pass the Ticket]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

To contain the impact of a previously generated golden ticket, reset the built-in KRBTGT account password twice, which will invalidate any existing golden tickets that have been created with the KRBTGT hash and other Kerberos tickets derived from it.(Citation: ADSecurity Kerberos and KRBTGT) For each domain, change the KRBTGT account password once, force replication, and then change the password a second time. Consider rotating the KRBTGT account password every 180 days.(Citation: STIG krbtgt reset)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--918a7d67-faea-4a41-9ed3-e3558fca73db`.
