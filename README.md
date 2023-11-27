## Diagram: YouTube Video to Human Summary

```mermaid
graph LR
    A[YouTube Video] -->|Generate| B[Document 1]
    A -->|Generate| C[Document 2]
    A -->|Generate| D[Document 3]
    B -->|Summarize| E[Summary 1]
    C -->|Summarize| F[Summary 2]
    D -->|Summarize| G[Summary 3]
    E -->|Combine| H[Summary]
    F -->|Combine| H
    G -->|Combine| H
    H -->|Review| I[Human]
