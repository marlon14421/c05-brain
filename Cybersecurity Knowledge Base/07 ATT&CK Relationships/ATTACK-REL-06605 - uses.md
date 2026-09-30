---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1020"
target_object: "T1608.006"
stix_relationship_id: "relationship--8ffd5c6a-da54-43ee-b384-7458499302ad"
---
# Relationship 6605: G1020 — uses → T1608.006

**Source object:** [[01 ATT&CK/G1020 - Mustard Tempest|G1020: Mustard Tempest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.006 - SEO Poisoning|T1608.006: SEO Poisoning]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustard Tempest](https://attack.mitre.org/groups/G1020) has poisoned search engine results to return fake software updates in order to distribute malware.(Citation: Microsoft Ransomware as a Service)(Citation: SocGholish-update)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ffd5c6a-da54-43ee-b384-7458499302ad`.
