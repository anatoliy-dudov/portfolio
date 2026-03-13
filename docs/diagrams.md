# Incident workflow

```mermaid
graph TD

A[Alert] --> B{Impact confirmed?}
B -->|Yes| C[Create Incident]
B -->|No| D[Close Alert]
C --> E[Notify Teams]
E --> F[Resolve Incident]
