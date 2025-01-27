# Restaurant Ordering Process

```mermaid
flowchart TD
  A[Welcome to the Restaurant] --> B{Have you decided on a dish?}
  B -- Yes --> C[Place the Order]
  B -- No --> D[View Menu]
  D --> B
  C --> E[Meal is Prepared]
  E --> F[Receive the Meal]
