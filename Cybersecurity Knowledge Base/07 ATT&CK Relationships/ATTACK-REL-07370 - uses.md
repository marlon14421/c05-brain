---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1052"
target_object: "T1684.001"
stix_relationship_id: "relationship--93746e56-c2da-4186-acad-3a212537d764"
---
# Relationship 7370: G1052 — uses → T1684.001

**Source object:** [[01 ATT&CK/G1052 - Contagious Interview|G1052: Contagious Interview]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Contagious Interview](https://attack.mitre.org/groups/G1052) had impersonated HR hiring personnel through social media, job board notifications, and conducted interviews with victims in order to entice them to download malware disguised as legitimate applications or malicious scripts from code repositories.(Citation: Sentinel One Contagious Interview ClickFix September 2025)(Citation: Validin Contagious Interview North Korea ClickFix January 2025)(Citation: Socket HexEval BeaverTail Contagious Interview June 2025)(Citation: SecurityScorecard Contagious Interview October 2024)(Citation: Securonix Contagious Interview DEVPOPPER April 2024)(Citation: SecurityScorecard Contagious Interview FamousChollima October 2024)(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023)(Citation: PaloAlto Unit42 ContagiousInterview BeaverTail InvisibileFerret October 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--93746e56-c2da-4186-acad-3a212537d764`.
