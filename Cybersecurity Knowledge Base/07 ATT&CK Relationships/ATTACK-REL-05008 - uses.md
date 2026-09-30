---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0148"
target_object: "T1102.001"
stix_relationship_id: "relationship--954c6284-d1eb-48f1-96a4-1ed81b063d82"
---
# Relationship 5008: S0148 — uses → T1102.001

**Source object:** [[01 ATT&CK/S0148 - RTM|S0148: RTM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.001 - Dead Drop Resolver|T1102.001: Dead Drop Resolver]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RTM](https://attack.mitre.org/software/S0148) has used an RSS feed on Livejournal to update a list of encrypted C2 server names. [RTM](https://attack.mitre.org/software/S0148) has also hidden [Pony](https://attack.mitre.org/software/S0453) C2 server IP addresses within transactions on the Bitcoin and Namecoin blockchain.(Citation: ESET RTM Feb 2017)(Citation: CheckPoint Redaman October 2019)(Citation: Unit42 Redaman January 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--954c6284-d1eb-48f1-96a4-1ed81b063d82`.
