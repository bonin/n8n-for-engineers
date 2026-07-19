# Terminology

| Preferred | Avoid | Reason |
|---|---|---|
| workflow execution | run, job | Precise in n8n context |
| item | record, row | Matches n8n's data model |
| trigger node | starter node | Official concept |
| credential | login | May be a key, token, password, or OAuth grant |
| retry | rerun | Retry belongs to a failure policy |
| replay | retry | Replay may repeat completed work |
| idempotency | duplicate prevention | More accurate and broader |
| production environment | live | Avoids ambiguity |
