---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9035"
target_object: "T1566.001"
stix_relationship_id: "relationship--bd097aa0-33e4-47a7-8ef4-b765aae9e76f"
---
# Relationship 9260: S9035 — uses → T1566.001

**Source object:** [[01 ATT&CK/S9035 - LAMEHUG|S9035: LAMEHUG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LAMEHUG](https://attack.mitre.org/software/S9035) has been distributed through spearphishing emails with various AI-themed malicious attachments.(Citation: Splunk LAMEHUG SEP 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd097aa0-33e4-47a7-8ef4-b765aae9e76f`.
