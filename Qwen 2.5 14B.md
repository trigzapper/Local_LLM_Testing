Installing a 14B Qwen Model

There are excellent 14B options in the Qwen 2.5 lineup (which require roughly 9–10 GB of VRAM/RAM to run smoothly):

General Purpose (Chat & Instruct):

Best for general conversation, writing, reasoning, and standard tasks.

Bash
ollama run qwen2.5:14b
Coding & Development Focus (Qwen 2.5 Coder 14B):

If you plan to use the model for programming, debugging, or integrating with code editors (like Cursor or VS Code), qwen2.5-coder:14b is widely regarded as one of the best open-source coding models available for its size.

Bash
ollama run qwen2.5-coder:14b
Useful Ollama Commands
List installed models: ollama list

Remove a model to free disk space: ollama rm qwen2.5:7b

Stop a running model: ollama stop qwen2.5:7b