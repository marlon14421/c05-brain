---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0058"
target_object: "T1074.001"
stix_relationship_id: "relationship--9ff590a0-b722-4282-8644-ff7344ac54b2"
---
# Relationship 3485: C0058 — uses → T1074.001

**Source object:** [[01 ATT&CK/C0058 - SharePoint ToolShell Exploitation|C0058: SharePoint ToolShell Exploitation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [SharePoint ToolShell Exploitation](https://attack.mitre.org/campaigns/C0058), threat actors staged stolen data from web.config files to debug_dev.js.(Citation: Palo Alto SharePoint Vulnerabilities JUL 2025)(Citation: Trend Micro SharePoint Attacks JUL 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ff590a0-b722-4282-8644-ff7344ac54b2`.
