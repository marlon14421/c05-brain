---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0058"
target_object: "T1620"
stix_relationship_id: "relationship--e54aad60-0f67-4eef-b269-5c783dc98748"
---
# Relationship 9735: C0058 — uses → T1620

**Source object:** [[01 ATT&CK/C0058 - SharePoint ToolShell Exploitation|C0058: SharePoint ToolShell Exploitation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1620 - Reflective Code Loading|T1620: Reflective Code Loading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [SharePoint ToolShell Exploitation](https://attack.mitre.org/campaigns/C0058), threat actors reflectively loaded payloads using `System.Reflection.Assembly.Load`.(Citation: Microsoft SharePoint Exploit JUL 2025)(Citation: Eye Research ToolShell JUL 2025)(Citation: Trend Micro SharePoint Attacks JUL 2025)(Citation: SentinelOne ToolShell JUL 2025)(Citation: Palo Alto SharePoint Vulnerabilities JUL 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e54aad60-0f67-4eef-b269-5c783dc98748`.
