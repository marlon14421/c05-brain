---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9044"
target_object: "T1550.001"
stix_relationship_id: "relationship--c80bc262-246d-40a1-9216-7b18b50fb6e6"
---
# Relationship 7108: S9044 — uses → T1550.001

**Source object:** [[01 ATT&CK/S9044 - Kali365|S9044: Kali365]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1550.001 - Application Access Token|T1550.001: Application Access Token]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kali365](https://attack.mitre.org/software/S9044) has utilized an Exchange Admin module that captured admin tokens to create rogue mailbox connectors and change mail-flow rules.(Citation: Huntress Kali365 Device Code June 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c80bc262-246d-40a1-9216-7b18b50fb6e6`.
