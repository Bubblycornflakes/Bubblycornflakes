<div align="center">

# Aslam Sheik Alaudeen

**Builds AI tools that run on your own machine, and measures whether they work.**

MSc Engineering with Innovation and Entrepreneurship, UCL · BEng Mechanical Engineering · London

[Featured projects](#featured-projects) · [How I work](#how-i-work) · [Skills](#skills) · [Contact](#contact)

</div>

---

## Featured projects

### Consultation AI Eval: does an AI interviewer take a good history, and does it treat everyone the same?

A pilot study. A local language model plays a clinician and takes a history from a simulated patient (also a model, with hidden facts it should only reveal when asked). A scorer counts which facts the interviewer uncovered and whether it gave advice, then every case is rerun with only the patient's age or gender changed.

| | |
|---|---|
| **Method** | Five fictional cases, a gate that shows the patient only the facts a question relates to, a rule-based scorer, and age and gender swaps |
| **Finding** | The gate removed clear fact leaks (2 of 5 conversations before, 0 of 15 after) but not invented details (5 of 5, then 12 of 15) |
| **Check on my own scorer** | I labelled 8 blind transcripts by hand: 67% agreement on 103 facts, Cohen's kappa 0.37, and the scorer only ever over-counted |
| **Limits, stated up front** | Small local models, 15 conversations that are really 7 distinct transcripts, no real patient data, nothing here shows bias |

[**See the project →**](https://github.com/Bubblycornflakes/consultation-ai-eval)

### J.A.R.V.I.S., a local voice assistant for macOS

Say "Jarvis" and a language model running on your own Mac decides what to do, uses tools to do it, and answers out loud.

| | |
|---|---|
| **Listens** | Wake word, then Whisper large-v3 turbo (MLX) for speech to text |
| **Thinks** | Local model via Ollama choosing from about 30 tools |
| **Fast lane** | Rule-matched commands (lights, volume, music) run instantly with no model call |
| **Speaks** | Streams replies sentence by sentence with a local Kokoro voice |
| **Measured** | A small local model (qwen3:4b) picked the right tool on **95% of 43 labelled requests, up from 86%** after I rewrote the tool descriptions. I tuned on those same cases, so it is a score on the cases I fixed against, not a benchmark |

[**See the project →**](https://github.com/Bubblycornflakes/jarvis-local-voice-assistant)

### Maple & Oak: QR table ordering and restaurant analytics

A phone ordering menu for a sit-down restaurant, an owner console for the kitchen, and Python scripts that analyse a year of trading: menu profit, demand forecasts, staffing, supplier prices, reviews and waste. It ships with a simulated restaurant, and the README says so: nothing in it is a real restaurant's data.

[**See the project →**](https://github.com/Bubblycornflakes/maple-oak-diner)

## How I work

- **Evaluate before trusting.** I measure how often a system gets it right, look at where it fails, then fix the cause instead of guessing.
- **Say what the numbers cannot show.** My READMEs lead with limitations, small samples and what was not tested.
- **Run it locally.** Speech, language model and voice all run on my own Mac, with data kept on the machine.
- **Make it usable by others.** Every repo aims to be something a stranger can read, run and trust.

## Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

LLM tool calling · agent and conversation evaluation · experiment design · local speech recognition and synthesis · MCP servers · engineering and entrepreneurship

## Currently exploring

- How tool-using agents fail, and how clearer tool descriptions fix them
- How conversational agents gather information, and how to test them fairly
- Comparing small local models on speed and accuracy

## Contact

- Email: [bubcflake@gmail.com](mailto:bubcflake@gmail.com)

Questions about any project? Open an issue on the repo. I read them.
