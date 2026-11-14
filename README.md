# InkMind

AI Chat of [InkDOS Hub](https://inkdoshub.github.io/): small GGUF models (Qwen, Llama) running on the device with wllama (llama.cpp in wasm).

- Web app: https://inkdoshub.github.io/InkMind/ (root of this repository, GitHub Pages)
- Models are downloaded once through the Hub's Cloudflare Worker (`/InkMind/modelos/*`) and kept in the browser storage.
- In the Hub's Windows app the models run on native llama.cpp (`windows/hub/ia.js` in the Hub repository).

Shared Hub files (theme, language, bar, document readers) come from the same site.
