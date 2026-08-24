
```mermaid
classDiagram

    class User {
        +String name
    }

    class Account {
        +String number
        +String agency
        +double balance
        +double limit
    }

    class Pix {
        +String icon
        +String description
    }

    class Pay {
        +String icon
        +String description
    }

    class Transfer {
        +String icon
        +String description
    }

    class Card {
        +String number
        +double limit
    }

    class News {
        +String icon
        +String description
    }

    User "1" *-- "1" Account
    User "1" *-- "1" Pix
    User "1" *-- "1" Pay
    User "1" *-- "1" Transfer
    User "1" *-- "1" Card
    User "1" *-- "1" News
```mermaid
