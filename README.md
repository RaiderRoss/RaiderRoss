## 📊 Academic Progress

```mermaid
flowchart TD
    classDef core fill:#f9f,stroke:#333,stroke-width:2px,color:#000;
    classDef backend fill:#bbf,stroke:#333,stroke-width:2px,color:#000;
    classDef elective fill:#ffb,stroke:#333,stroke-width:2px,color:#000;
    classDef advanced fill:#bfb,stroke:#333,stroke-width:2px,color:#000;

    subgraph Year1["Year 1"]
        COS110["COS 110<br>81%"]:::core
        COS216["COS 216<br>81%"]:::elective
    end

    subgraph Year2["Year 2"]
        COS212["COS 212<br>83%"]:::backend
        COS210["COS 210<br>77%"]:::backend
        COS314["COS 314<br>75%"]:::elective
        COS344["COS 344<br>80%"]:::elective
    end

    subgraph Year3["Year 3"]
        COS214["COS 214<br>87%"]:::advanced
        COS226["COS 226<br>81%"]:::advanced
        COS284["COS 284<br>79%"]:::advanced
        COS332["COS 332<br>75%"]:::advanced
    end

    COS110 --> COS212
    COS110 --> COS210
    COS110 --> COS314
    COS110 --> COS344
    COS110 --> COS216

    COS212 --> COS214
    COS212 --> COS226
    COS210 --> COS284
    COS216 --> COS332

    linkStyle default stroke:#333, stroke-width:2px

