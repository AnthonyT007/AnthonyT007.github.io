```mermaid
erDiagram
PRODUCT {
}
CUSTOMER {
}
SALE {
}
INVENTORY {
}
```
```mermaid
erDiagram
    CUSTOMER ||--o{ Product : buys
    Inventory ||--|{ Sale : checks_stock_on_item
    CUSTOMER }|..|{ Product : uses
```
```mermaid
erDiagram
    CUSTOMER ||--o{ Product : buys
    Product {
        Shoe Air_Forces
        Shoe Air_Max
        Shoe Training_Shoe
    }
    INVENTORY ||--o{ Sale : is_checked
    Sale {
        Shoe Air_Forces
        Shoe Air_Max
        Shoe Training_shoe
    }

```
