---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0035"
target_object: "T1190"
stix_relationship_id: "relationship--d06cd799-f61b-460e-a287-e58e8ff39022"
---
# Relationship 8005: G0035 — uses → T1190

**Source object:** [[01 ATT&CK/G0035 - Dragonfly|G0035: Dragonfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dragonfly](https://attack.mitre.org/groups/G0035) has conducted SQL injection attacks, exploited vulnerabilities CVE-2019-19781 and CVE-2020-0688 for Citrix and MS Exchange, and CVE-2018-13379 for Fortinet VPNs.(Citation: CISA AA20-296A Berserk Bear December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d06cd799-f61b-460e-a287-e58e8ff39022`.
