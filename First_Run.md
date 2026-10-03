Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

PS C:\Users\ssury> ollama run qwen3.8:27b
pulling manifest
pulling ac3714bfddde: 100% ▕██████████████████████████████████████████████████████████▏ 931 MB
pulling f5f1dd8920d4: 100% ▕██████████████████████████████████████████████████████████▏  16 GB
verifying sha256 digest
writing manifest
success
>>>
>>> ollama ps
Thinking...
The user typed "ollama ps" which is a command-line instruction. Let me think about what this means.

"ollama ps" is a command you run in a terminal to list the models currently loaded in memory by the Ollama server.
It's similar to how `docker ps` lists running containers.

The user seems to be either:
1. Asking me what the `ollama ps` command does
2. Trying to run a command in a chat (thinking I'm a terminal)
3. Asking for help with Ollama

I'll explain what `ollama ps` does since I can't actually execute commands. Let me provide a helpful explanation
of what this command does and what its output looks like.
...done thinking.

I can't execute terminal commands, but I can tell you what **`ollama ps`** does:

## `ollama ps`

Lists the models currently **loaded in memory** by the Ollama server (similar to `docker ps` for containers).

### Typical output:

```
NAME            ID              SIZE      PROCESSOR    UNTIL
llama3:8b       5f0c2c59a9b7   4.9 GB    100% GPU     5 minutes from now
mistral:7b      60e1d38a25c2   4.4 GB   100% GPU     5 minutes from now
```

### Columns:

| Column | Meaning |
|--------|---------|
| **NAME** | Model name + tag |
| **ID** | Short hash of the model |
| **SIZE** | VRAM/RAM used |
| **PROCESSOR** | Where it's running (CPU, GPU, split) |
| **UNTIL** | When Ollama will unload it from memory |

### Related commands:

- **`ollama list`** – shows all *available* (downloaded) models, not just loaded ones.
- **`ollama stop <model>`** – immediately unloads a model from memory.
- **`ollama serve`** – starts the Ollama background server (if it isn't running).

### Quick tip
If `ollama ps` shows no models, the server might not be running. Try:
```bash
ollama serve &   # start the server
ollama ps        # check again
```

---

Were you troubleshooting something specific with Ollama?


PS C:\Users\ssury> ollama run qwen3.8:27b
>>> /set parameter num_ctx 8192
Set parameter 'num_ctx' to '8192'
>>> hey
Thinking...
The user said "hey" - this is a casual greeting. I should respond in a friendly, casual manner and offer to help with whatever they need.
...done thinking.

Hey! How's it going? What can I help you with today?

>>> Send a message (/? for help)