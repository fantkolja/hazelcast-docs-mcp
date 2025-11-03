┌────────────────────────────┐      ┌─────────────────────────────┐      ┌─────────────────────────────┐      ┌─────────────────────────────┐
│  LLM Integration Layer     ├─────▶│  Context Generation Layer   ├─────▶│  MCP Server Layer           │─────▶│ Documentation Website Layer │
│  - Uses context via MCP    │      │  - Prepares structured data │      │  - Exposes resources/tools  │      │ - Canonical documentation   │
│  - Generates responses     │      │  - Runs asynchronously      │      │  - Manages protocol logic   │      │ - Static site (Antora etc.) │
└────────────────────────────┘      └─────────────────────────────┘      └─────────────────────────────┘      └─────────────────────────────┘
