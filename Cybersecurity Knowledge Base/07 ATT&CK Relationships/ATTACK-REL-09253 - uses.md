---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0040"
target_object: "T1566.001"
stix_relationship_id: "relationship--5b63f8fd-efc7-454f-b466-d5e0a525f64f"
---
# Relationship 9253: G0040 — uses → T1566.001

**Source object:** [[01 ATT&CK/G0040 - Patchwork|G0040: Patchwork]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Patchwork](https://attack.mitre.org/groups/G0040) has used spearphishing with an attachment to deliver files with exploits to initial victims.(Citation: Cymmetria Patchwork)(Citation: Securelist Dropping Elephant)(Citation: TrendMicro Patchwork Dec 2017)(Citation: Volexity Patchwork June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b63f8fd-efc7-454f-b466-d5e0a525f64f`.
