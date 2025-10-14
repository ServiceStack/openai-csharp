## C# Client Example for OpenAI Chat Completions API

Run the example:

```bash
dotnet run
```

Add just the `ChatCompletion` and its dependent DTOs:

```bash
npx get-dtos csharp https://localhost:5001 --include "ChatCompletion.*"
```

Alternatively, add all DTOs:

```bash
npx get-dtos csharp https://localhost:5001
```

Update DTOs:

```bash
npx get-dtos csharp
```