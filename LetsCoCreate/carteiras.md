```mermaid
flowchart TD
    A(["Chave Privada"]) --> B["Chave Pública #1"] & n1@{ label: "<span style=\"padding-left:\">Chave Pública #2</span>" } & n2@{ label: "<span style=\"padding-left:\"><span style=\"padding-left:\">Chave Pública #3</span></span>" }
    B@{ shape: rect}
    n1@{ shape: rect}
    n2@{ shape: rect}
```
```mermaid
flowchart TD
    A(["BOB"]) -- Assina com a chave privada --> n1["Transação"]
    n1 -- Transmitida --> n2["Blockchain"]
    n2 -- Minera --> n3(["Alice"])
    n1@{ shape: rect}
```
```mermaid
flowchart TD
    A(["Chave Privada"]) --> B["Chave Pública #1"] & n1@{ label: "<span style=\"padding-left:\">Chave Pública #2</span>" } & n2@{ label: "<span style=\"padding-left:\"><span style=\"padding-left:\">Chave Pública #3</span></span>" }
    B --> n3["endereço #1"] & n4@{ label: "<span style=\"padding-left:\">endereço #2</span>" } & n5@{ label: "<span style=\"padding-left:\">endereço #3</span>" }
    n1 --> n6@{ label: "<span style=\"padding-left:\">endereço #1</span>" }
    n2 --> n7@{ label: "<span style=\"padding-left:\">endereço #1</span>" } & n8@{ label: "<span style=\"padding-left:\"><span style=\"padding-left:\">endereço #2</span></span>" }
    B@{ shape: rect}
    n1@{ shape: rect}
    n2@{ shape: rect}
    n4@{ shape: rect}
    n5@{ shape: rect}
    n6@{ shape: rect}
    n7@{ shape: rect}
    n8@{ shape: rect}
```
