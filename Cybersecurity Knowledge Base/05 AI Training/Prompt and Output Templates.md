# Prompt and Output Templates

## Retrieval-grounded answer

```text
Task: Answer the defensive security question using retrieved vault records.
Context: [authorized environment, versions, assets, telemetry]
Evidence: [source IDs, short excerpts, source links, retrieval date]
Rules: Preserve source wording and relationship direction. Mark inference.
Do not infer compromise, exploitability, attribution, or installed controls from catalog records alone.
If context is missing, ask a focused question. Recommend only authorized, defensive steps.
Output: finding / evidence / confidence and limits / safe next checks / citations.
```

## CWE triage response

```text
Observed condition: ...
Candidate CWE(s): ... (confirmed / tentative)
Evidence that matches the definition: ...
Evidence still needed: ...
Impact and reachability in this system: ...
Candidate remediation and regression test: ...
Source links: ...
```

## Detection hypothesis

```text
Behavior to detect: ...
ATT&CK mapping (hypothesis): ...
Data sources and required fields: ...
Expected signal: ...
Benign lookalikes: ...
Lab validation and success criteria: ...
Coverage gaps and response owner: ...
Source IDs: ...
```

## Relationship explanation

```text
The catalog records [source ID] --[typed relationship]--> [target ID].
This means: [plain-language meaning].
It does not establish: [environmental fact not evidenced].
Source snapshot and linked records: ...
```

## Retrieval quality checks

- Are exact identifiers and title matches included in search?
- Were both endpoints fetched for a relationship?
- Is the source snapshot fresh enough for the task?
- Does the cited passage actually support each claim?
- Did the answer distinguish absence of evidence from evidence of absence?
- Are proposed tests authorized, reversible, and safe for the target environment?
