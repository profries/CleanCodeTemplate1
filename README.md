# CleanCodeTemplate1

<h1>Luis Henrique Leal Ries</h1>

<h4>Projeto voltado para mostrar o template padrão </h4>

```
- database/
    - migrations/
- docs/
- public/
    - assets/
- src/
    - models/
- testes/
```

OU
```
. 
├── src/ # Código-fonte principal da aplicação 
│    ├── Application/ # 1. Casos de Uso (Use Cases) e Lógica de Aplicação 
│    ├── Domain/ # 2. O Coração do Negócio (Entidades e Interfaces) 
│    └── Infrastructure/ # 3. Adapters e Implementações (Persistência, APIs Externas) 
├── tests/ # Testes (unitários e de integração) 
├── .gitignore 
├── LICENSE 
└── README.md
```