<p align="center">
  <img src="https://github.com/ontypehq/.github/raw/main/assets/hero-glow.png" alt="OnType" width="128" />
</p>

<h3 align="center">Speak, and it types.</h3>

<p align="center">
  The fastest way to input text on macOS.<br>
  Hold a key, say what you mean, and watch it appear — anywhere, instantly.
</p>

<p align="center">
  <a href="https://getontype.app"><strong>Website</strong></a> ·
  <a href="https://github.com/ontypehq/OnType/releases"><strong>Download</strong></a>
</p>

---

### How it works

**Hold** your hotkey → **Speak** naturally → **Release** to type. That's it.

OnType uses on-device AI to transcribe your voice in real time. Your audio never leaves your Mac.

### Highlights

- **On-device ASR** — Powered by [MLX](https://github.com/ml-explore/mlx) on Apple Silicon. No cloud, no latency, no subscriptions.
- **Works everywhere** — Any text field in any app. Xcode, Slack, Notes, browsers, terminals.
- **AI rewriting** — Optionally clean up grammar, formatting, or tone after transcription.
- **Privacy by default** — 100% offline capable. Zero telemetry. Your voice data stays on your machine.

### Tech

| | |
|---|---|
| **Runtime** | Swift 6.2+, macOS 15+ (Sequoia) |
| **Inference** | MLX (Apple Silicon optimized) |
| **ASR Model** | Qwen3-ASR |
| **Text insertion** | Accessibility API → CGEvent → Pasteboard (3-tier fallback) |

### Projects

| Repo | Description |
|------|-------------|
| [**OnType**](https://github.com/ontypehq/OnType) | The main macOS app |
| [**libfst**](https://github.com/ontypehq/libfst) | Finite-state transducer library for text normalization |
