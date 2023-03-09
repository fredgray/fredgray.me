```mermaid
erDiagram
  Employers ||--o{Employees: contains
  Employers {
    string id PK
    string client_id FK
    int fein
    string gname
  }
