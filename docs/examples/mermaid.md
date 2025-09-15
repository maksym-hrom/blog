---
id: mermaid-example
title: Mermaid Example
---

Below are example Mermaid diagrams to verify rendering in Docusaurus.

```mermaid
flowchart TD
  A[Start] --> B{Is it working?}
  B -- Yes --> C[Ship it]
  B -- No --> D[Check config]
  D --> B
```

```mermaid
sequenceDiagram
  participant U as User
  participant S as Site
  U->>S: Open page
  S-->>U: Render Mermaid diagram
```

