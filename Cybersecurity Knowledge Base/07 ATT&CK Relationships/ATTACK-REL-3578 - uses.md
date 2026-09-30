---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0058"
target_object: "T1190"
stix_relationship_id: "relationship--6cfdc8e4-4970-428b-80c3-89ebb12328c4"
---
# Relationship 3578: C0058 — uses → T1190

**Source object:** [[01 ATT&CK/C0058 - SharePoint ToolShell Exploitation|C0058: SharePoint ToolShell Exploitation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [SharePoint ToolShell Exploitation](https://attack.mitre.org/campaigns/C0058), threat actors exploited authentication bypass and remote code execution vulnerabilities (CVE-2025-49706 and CVE-2025-49704) against on-premises SharePoint servers. This activity was characterized by crafted `POST` requests to the ToolPane endpoint `/_layouts/15/ToolPane.aspx`.(Citation: Microsoft SharePoint Exploit JUL 2025)(Citation: ESET ToolShell JUL 2025)(Citation: Eye Research ToolShell JUL 2025)(Citation: Trend Micro SharePoint Attacks JUL 2025)(Citation: SentinelOne ToolShell JUL 2025)(Citation: Palo Alto SharePoint Vulnerabilities JUL 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6cfdc8e4-4970-428b-80c3-89ebb12328c4`.
