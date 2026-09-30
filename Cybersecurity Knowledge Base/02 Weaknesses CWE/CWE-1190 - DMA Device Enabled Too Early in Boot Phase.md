---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1190"
status: "Draft"
---
# CWE-1190: DMA Device Enabled Too Early in Boot Phase

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, System on Chip

## Description

The product enables a Direct Memory Access (DMA) capable device before the security configuration settings are established, which allows an attacker to extract data from or gain privileges on the product.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Utilize an IOMMU to orchestrate IO access from the start of the boot process.

## Related weaknesses

- CWE-696 (ChildOf)

## Source

- [CWE-1190 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1190.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
