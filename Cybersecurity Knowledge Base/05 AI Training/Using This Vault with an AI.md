# Using This Vault with an AI

## What is in the knowledge base

The vault has source records from MITRE ATT&CK (behaviors, mitigations, detection analytics, software and groups), CWE (software weakness classes), and CAPEC (attack patterns). The added ATT&CK relationship notes make explicit connections between records. A relationship is a catalog claim with direction and type; it does not prove that a behavior happened in a particular environment.

## Recommended architecture

1. **Ingest:** read Markdown and YAML; retain file path, source URL, source identifier, dataset version or retrieval date, and relationship direction.
2. **Normalize:** split each note into title, metadata, description, defensive interpretation, and provenance. Keep one note as one retrievable unit unless it is unusually long.
3. **Index:** combine keyword/BM25 search with semantic embeddings. Keep exact IDs searchable as literal terms. Add filters for source, note type, platform, and relationship.
4. **Retrieve:** search the user's task and environment context; fetch the best source notes and the endpoint records for any relationship. Prefer official, current documentation when the question is product/version specific.
5. **Answer:** state findings, distinguish source facts from inference, cite note identifiers and links, note uncertainty, and propose only authorized, defensive actions.
6. **Verify:** check every cited identifier exists; verify the citation supports the sentence; ask for missing system context rather than invent it.

## Minimal retrieval pseudocode

```text
question + authorized environment context
  -> parse task type (learn, classify, detect, respond)
  -> retrieve exact IDs + keyword matches + semantic matches
  -> expand typed ATT&CK edges to linked endpoint records
  -> rank by relevance, source quality, freshness, and applicability
  -> draft answer using only retrieved evidence
  -> validate citations, direction of edges, and safe-action constraints
  -> return answer with unknowns and next verification step
```

An embedding score is a search hint, not a truth score. The model should never claim a control is present or an intrusion occurred just because related notes were retrieved.
