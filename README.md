# Ricardo Rencoret Nicolás

I build Flutter apps and Python services at [RENCORET AI](https://github.com/rencoretai). I also run language models on Apple Silicon and document what I can reproduce on my own hardware.

## Local AI on Apple Silicon

I converted a 27B Qwen-based model to MLX in two sizes. On an M1 Max with 32 GiB of unified memory, the 6-bit version handled short text and tool-call tests in oMLX's text-only mode. The model cards include the setup, sample tasks and memory limits.

[4-bit model and setup](https://huggingface.co/uzzero/Qwen3.8-27B-OBLITERATED-Mythos-Class-Agentic-MLX-4bit) · [6-bit model and test results](https://huggingface.co/uzzero/Qwen3.8-27B-OBLITERATED-Mythos-Class-Agentic-MLX-6bit)

## Selected open-source contributions

- **ChatView** — Fixed a Flutter build failure after the emoji picker's recent-tab API changed. [Merged pull request](https://github.com/SimformSolutionsPvtLtd/chatview/pull/94)
- **geocode** — Fixed how the Dart client passes the authentication parameter when looking up an address or converting coordinates back to one. [Merged pull request](https://github.com/imvalient/geocode/pull/16)

[Hugging Face](https://huggingface.co/uzzero) · [LinkedIn](https://www.linkedin.com/in/ricardo-rencoret) · [rencoret.ai](https://rencoret.ai/)
