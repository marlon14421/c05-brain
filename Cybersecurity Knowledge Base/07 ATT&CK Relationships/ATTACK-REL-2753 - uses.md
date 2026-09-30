---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0658"
target_object: "T1056.002"
stix_relationship_id: "relationship--b019c5ea-be5e-453a-9ed6-e86384c92259"
---
# Relationship 2753: S0658 — uses → T1056.002

**Source object:** [[01 ATT&CK/S0658 - XCSSET|S0658: XCSSET]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.002 - GUI Input Capture|T1056.002: GUI Input Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[XCSSET](https://attack.mitre.org/software/S0658) prompts the user to input credentials using a native macOS dialog box leveraging the system process /Applications/Safari.app/Contents/MacOS/SafariForWebKitDevelopment .(Citation: trendmicro xcsset xcode project 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b019c5ea-be5e-453a-9ed6-e86384c92259`.
