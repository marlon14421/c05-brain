---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1027.013"
stix_relationship_id: "relationship--1b143de7-af2d-4991-9e2e-aa85a8d7d330"
---
# Relationship 6846: G0007 — uses → T1027.013

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) encrypted a .dll payload using RTL and a custom encryption algorithm. [APT28](https://attack.mitre.org/groups/G0007) has also obfuscated payloads with base64, XOR, and RC4.(Citation: Bitdefender APT28 Dec 2015)(Citation: Unit 42 Sofacy Feb 2018)(Citation: Palo Alto Sofacy 06-2018)(Citation: Talos Seduploader Oct 2017)(Citation: Accenture SNAKEMACKEREL Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1b143de7-af2d-4991-9e2e-aa85a8d7d330`.
