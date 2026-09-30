---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0283"
target_object: "T1027"
stix_relationship_id: "relationship--ec2e27c9-71fe-4650-a5b9-1247193c39f6"
---
# Relationship 3366: S0283 — uses → T1027

**Source object:** [[01 ATT&CK/S0283 - jRAT|S0283: jRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[jRAT](https://attack.mitre.org/software/S0283)’s Java payload is encrypted with AES.(Citation: jRAT Symantec Aug 2018) Additionally, backdoor files are encrypted using DES as a stream cipher. Later variants of [jRAT](https://attack.mitre.org/software/S0283) also incorporated AV evasion methods such as Java bytecode obfuscation via the commercial Allatori obfuscation tool.(Citation: Symantec Frutas Feb 2013)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec2e27c9-71fe-4650-a5b9-1247193c39f6`.
