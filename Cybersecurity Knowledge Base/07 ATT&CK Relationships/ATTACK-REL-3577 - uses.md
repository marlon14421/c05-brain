---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0066"
target_object: "T1573.001"
stix_relationship_id: "relationship--0e630f6b-8662-4ffe-b666-709e17aad69f"
---
# Relationship 3577: S0066 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0066 - 3PARA RAT|S0066: 3PARA RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[3PARA RAT](https://attack.mitre.org/software/S0066) command and control commands are encrypted within the HTTP C2 channel using the DES algorithm in CBC mode with a key derived from the MD5 hash of the string HYF54&%9&jkMCXuiS. [3PARA RAT](https://attack.mitre.org/software/S0066) will use an 8-byte XOR key derived from the string HYF54&%9&jkMCXuiS if the DES decoding fails(Citation: CrowdStrike Putter Panda)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0e630f6b-8662-4ffe-b666-709e17aad69f`.
