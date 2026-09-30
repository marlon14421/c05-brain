---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-150"
status: "Incomplete"
---
# CWE-150: Improper Neutralization of Escape, Meta, or Control Sequences

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, AI/ML

## Description

The product receives input from an upstream component, but it does not neutralize or incorrectly neutralizes special elements that could be interpreted as escape, meta, or control character sequences when they are sent to a downstream component.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Mitigation:** Developers should anticipate that escape, meta and control characters/sequences will be injected/removed/manipulated in the input vectors of their product. Use an appropriate combination of denylists and allowlists to ensure only valid, expected and appropriate input is processed by the system.
- **Implementation:** While it is risky to use dynamically-generated query strings, code, or commands that mix control and data together, sometimes it may be unavoidable. Properly quote arguments and escape any special characters within those arguments. The most conservative approach is to escape or filter all characters that do not pass an extremely strict allowlist (such as everything that is not alphanumeric or white space). If some special characters are still needed, such as white space, wrap each argument in quotes after the escaping/filtering step. Be careful of argument injection (CWE-88).
- **Implementation:** Inputs should be decoded and canonicalized to the application's current internal representation before being validated (CWE-180). Make sure that the application does not decode the same input twice (CWE-174). Such errors could be used to bypass allowlist validation schemes by introducing dangerous inputs after they have been checked.
- **Implementation:** When using output from an LLM, neutralize or strip escape codes before redirecting output to the terminal or other rendering engine that would process the codes. The neutralization could require that the character be printable and/or allowable whitespace, such as a carriage return or newline. Be deliberate about what to allow.
- **Build and Compilation:** When using an LLM: during tokenizer training, suppress escape codes from the tokenizer's vocabulary. Depending on context, this could be accomplished by removing the codes from input to the tokenizer, or removing the map from the string to its token ID. It is generally unlikely that this removal would adversely affect the quality or correctness of what is generated, e.g. advice requests for terminal settings to change colors.

## Related weaknesses

- CWE-138 (ChildOf)

## Source

- [CWE-150 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/150.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
