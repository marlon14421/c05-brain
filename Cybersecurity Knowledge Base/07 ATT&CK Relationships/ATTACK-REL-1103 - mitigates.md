---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1015"
target_object: "T1558"
stix_relationship_id: "relationship--037b851b-7ced-4322-a57a-9f744f9a1e76"
---
# Relationship 1103: M1015 — mitigates → T1558

**Source object:** [[01 ATT&CK/M1015 - Active Directory Configuration|M1015: Active Directory Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1558 - Steal or Forge Kerberos Tickets|T1558: Steal or Forge Kerberos Tickets]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

For containing the impact of a previously generated golden ticket, reset the built-in KRBTGT account password twice, which will invalidate any existing golden tickets that have been created with the KRBTGT hash and other Kerberos tickets derived from it. For each domain, change the KRBTGT account password once, force replication, and then change the password a second time. Consider rotating the KRBTGT account password every 180 days.(Citation: STIG krbtgt reset)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--037b851b-7ced-4322-a57a-9f744f9a1e76`.
