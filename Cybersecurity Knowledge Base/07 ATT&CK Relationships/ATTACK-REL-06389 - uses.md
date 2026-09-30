---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0585"
target_object: "T1566.001"
stix_relationship_id: "relationship--4224c436-0960-4cea-b135-166008a1c087"
---
# Relationship 6389: S0585 — uses → T1566.001

**Source object:** [[01 ATT&CK/S0585 - Kerrdown|S0585: Kerrdown]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kerrdown](https://attack.mitre.org/software/S0585) has been distributed through malicious e-mail attachments.(Citation: Amnesty Intl. Ocean Lotus February 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4224c436-0960-4cea-b135-166008a1c087`.
