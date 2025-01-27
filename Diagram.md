# Restaurant Ordering Process
## I will be visualizing the process of ordering food at a restaurant

```mermaid
flowchart TD
  A[Joseph's sushi place] --> B{Do you know what sushi you want?}
  B -- Yes --> C[Order A La Carte]
  B -- No --> D[Sushi/Sashimi Menu]
  D --> B
  C --> E[Cutting fish and making sushi]
  E --> F[Enjoy]
