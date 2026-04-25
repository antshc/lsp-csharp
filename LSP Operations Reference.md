# LSP Operations Reference

| Operation | What triggers it / Use case | Required Parameters |
|---|---|---|
| `goToDefinition` | "Go to definition of X" / "Where is X defined?" | `file`, `line`, `character` |
| `findReferences` | "Find all usages of X" / "Who uses this symbol?" | `file`, `line`, `character` |
| `rename` | "Rename X to Y" / "Refactor symbol name across codebase" | `file`, `line`, `character`, `newName` |
| `hover` | "What type is X?" / "Show docs for X" | `file`, `line`, `character` |
| `documentSymbol` | "List all symbols in this file" / "What's in this file?" | `file` |
| `workspaceSymbol` | "Find symbol named X" / "Search for class/method by name" | `query` |
| `goToImplementation` | "Find implementations of interface X" / "Who implements this?" | `file`, `line`, `character` |
| `incomingCalls` | "What calls this function?" / "Find callers of X" | `file`, `line`, `character` |
| `outgoingCalls` | "What does this function call?" / "Show callees of X" | `file`, `line`, `character` |
