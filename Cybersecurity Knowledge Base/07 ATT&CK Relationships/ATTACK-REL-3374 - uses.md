---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1082"
stix_relationship_id: "relationship--e24411cf-6274-4b6b-87b4-b90b01146c8d"
---
# Relationship 3374: G0102 — uses → T1082

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has used [Systeminfo](https://attack.mitre.org/software/S0096) and similar commands to acquire detailed configuration information of a victim's machine. [Wizard Spider](https://attack.mitre.org/groups/G0102) has also utilized the PowerShell cmdlet `Get-ADComputer` to collect DNS hostnames, last logon dates, and operating system information from Active Directory.(Citation: DFIR Ryuk's Return October 2020)(Citation: Mandiant FIN12 Oct 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e24411cf-6274-4b6b-87b4-b90b01146c8d`.
