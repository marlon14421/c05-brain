---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1226"
target_object: "T1140"
stix_relationship_id: "relationship--7bfbdba0-2f18-4697-bf86-294bda685df5"
---
# Relationship 4951: S1226 — uses → T1140

**Source object:** [[01 ATT&CK/S1226 - BOOKWORM|S1226: BOOKWORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BOOKWORM](https://attack.mitre.org/software/S1226) has decoded its Base64 encoded payload prior to execution.(Citation: Palo Alto Networks, Unit 42) [BOOKWORM](https://attack.mitre.org/software/S1226) has also encrypted files with RC4 and has decrypted its payload prior to execution.(Citation: Unit42 Bookworm Nov2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7bfbdba0-2f18-4697-bf86-294bda685df5`.
