## Alberto Gonda

Engineer building agent harnesses and orchestrated LLM workflows.

The work is about making LLMs *do things* reliably — multi-tool routing, intent pre-classification, MCP integration, provider-aware prompt tier routing across model sizes. Two projects in active development at [@NerdoBaggins](https://github.com/NerdoBaggins):

- **Arcane Console** *(TypeScript / Electron)* — D&D 5e platform integrated with Claude Desktop via Model Context Protocol. Multi-tier LLM orchestrator on the Vercel AI SDK across Anthropic / OpenAI / Ollama, with deterministic intent pre-classification, prompt tier routing for compact vs. full-tier models, and 30+ unified MCP tools. Full D&D 5e game engine: registry-based derivation pipeline (100+ derived attributes), modular effect-contribution evaluation. ~4,100 tests passing.

- **Jarvis Listener** *(Python)* — voice harness for Claude Code. Wake-word ("Hey Jarvis") → local Moonshine ONNX STT → Claude → Voxtral TTS, with a Three.js orb visualizer reflecting real-time agent state via UDP→WebSocket. Vision watcher (OpenCV + YOLO11n) and home-automation layer for Apple TV / Samsung TV.

- **Arcane Classifier** *(JavaScript)* — NLP intent classifiers for Arcane Console: speech act recognition and domain routing.

Interested in MCP integration, multi-agent orchestration, and the infrastructure that makes LLMs behave like reliable runtimes, not chat.
