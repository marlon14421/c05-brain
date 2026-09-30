---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0027"
target_object: "T1190"
stix_relationship_id: "relationship--04e866d0-5d9d-435d-b37c-311bb0bbdb1e"
---
# Relationship 6785: C0027 — uses → T1190

**Source object:** [[01 ATT&CK/C0027 - C0027|C0027: C0027]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0027](https://attack.mitre.org/campaigns/C0027), [Scattered Spider](https://attack.mitre.org/groups/G1015) exploited CVE-2021-35464 in the ForgeRock Open Access Management (OpenAM) application server to gain initial access.(Citation: Crowdstrike TELCO BPO Campaign December 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--04e866d0-5d9d-435d-b37c-311bb0bbdb1e`.
