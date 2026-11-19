<div align="center">

# Aslam Sheik Alaudeen

**Builds AI tools that run on your own machine, and measures whether they work.**

MSc Engineering with Innovation and Entrepreneurship, UCL · London

[Featured project](#featured-project) · [What I do](#what-i-do) · [Skills](#skills) · [Contact](#contact)

</div>

---

## What I do

I build small, working AI systems and test them properly. My focus is local language models, tool-using agents and voice interfaces. I care about evidence over claims, so my projects ship with evaluations, tests and clear setup steps.

- **Evaluate before trusting.** I measure how often a model picks the right tool, then fix the cause instead of guessing.
- **Run it locally.** Speech, language model and voice all run on my own Mac, with data kept on the machine.
- **Make it usable by others.** Every repo aims to be something a stranger can read, run and trust.

## Featured project

### J.A.R.V.I.S., a local voice assistant for macOS

Say "Jarvis" and a language model running on your own Mac decides what to do, uses tools to do it, and answers out loud.

| | |
|---|---|
| **Listens** | Wake word, then Whisper large-v3 turbo (MLX) for speech to text |
| **Thinks** | Local model via Ollama choosing from about 30 tools |
| **Fast lane** | Rule-matched commands (lights, volume, music) run instantly with no model call |
| **Speaks** | Streams replies sentence by sentence with a local Kokoro voice |
| **Acts** | Apps, music, volume, calendar, web search, weather, journey times, smart lights, reminders, to-dos |

**Result I am proudest of:** a small local model (qwen3:4b) picked the right tool on **95% of 43 labelled requests, up from 86%** after I rewrote the tool descriptions. The evaluation harness, cases and raw results are in the repo.

[**See the project →**](https://github.com/Bubblycornflakes/jarvis-local-voice-assistant)

## Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

LLM tool calling · agent evaluation · local speech recognition and synthesis · MCP servers · product thinking and entrepreneurship

## Currently exploring

- How tool-using agents fail, and how clearer tool descriptions fix them
- Comparing small local models on speed and accuracy
- Video and content automation with AI agents

## Contact

- Email: [bubcflake@gmail.com](mailto:bubcflake@gmail.com)

Questions about any project? Open an issue on the repo. I read them.
