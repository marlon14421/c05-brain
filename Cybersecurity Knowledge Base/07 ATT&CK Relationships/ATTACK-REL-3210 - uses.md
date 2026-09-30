---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0386"
target_object: "T1027.013"
stix_relationship_id: "relationship--117ca63e-7fdb-41e6-9f4b-e19a0e889061"
---
# Relationship 3210: S0386 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0386 - Ursnif|S0386: Ursnif]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ursnif](https://attack.mitre.org/software/S0386) has used an XOR-based algorithm to encrypt Tor clients dropped to disk.(Citation: ProofPoint Ursnif Aug 2016) [Ursnif](https://attack.mitre.org/software/S0386) droppers have also been delivered as password-protected zip files that execute base64 encoded [PowerShell](https://attack.mitre.org/techniques/T1059/001) commands.(Citation: Bromium Ursnif Mar 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--117ca63e-7fdb-41e6-9f4b-e19a0e889061`.
