# 🏋️‍♂️ RepsAgent

**RepsAgent** is your personal AI-powered workout companion. It remembers your workouts, speaks out reps to guide your sessions, and adapts to your goals — all powered by OpenAI and written entirely in Rust.

## 🚀 Features
- 💬 Natural language interface (via OpenAI GPT)
- 🧠 Memory of previous workouts
- 🔁 Voice counting and motivation
- 📊 Progress tracking
- 🔧 Extendable tool system (Rust functions)

## 🛠 Planned Modules
- `core`: Agent runtime, OpenAI API, tools, memory
- `cli`: Command-line interface to interact with RepsAgent
- (future) `mobile`: Optional frontend (Tauri or Flutter shell)

## 🧪 Example usage
```bash
repsagent "Log 20 pushups"
repsagent "Count to 30 out loud"
repsagent "How many squats did I do this week?"
```

## 📦 Requirements
- Rust 1.75+
- OpenAI API key

## 📄 License
This project is licensed under the Business Source License 1.1 (BSL 1.1).

The source code is visible and open for review, but **commercial use is restricted until 2028-06-01**, after which it converts to **Apache-2.0**.

We believe in transparency and user control:
RepsAgent stores all workout data **locally** and does not collect telemetry.

See [LICENSE](./LICENSE) for full details.