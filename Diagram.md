# Restaurant Ordering Process

```mermaid
flowchart TD
  A[Joseph's sushi place] --> B{Do you know what sushi you want?}
  B -- Yes --> C[Order A La Carte]
  B -- No --> D[Sushi/Sashimi Menu]
  D --> B
  C --> E[Cutting fish and making sushi]
  E --> F[Enjoy]



I will be visualizing the process of ordering food at a restaurant

A: Entry point when a customer comes in.
B: Decision point to check if the customer have decided what fish they like.
C: If ready, they place the order.
D: If not ready, they can look at the menu.
E: Cheff cutting fish.
F: Customer enjoy the meal.
