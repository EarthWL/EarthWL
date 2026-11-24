# Hi, I'm Earth 👋

**Wanadtapong Lalakorn** · Nonthaburi, Thailand

Most of what's here started with "I wonder how that works." I take a
thing I use or need, then build my own version until I understand it:
desktop apps, AI tooling, document pipelines, small web toys. Some
become tools I use every day; some stay experiments.

---

## What I'm working on

### 🌸 Hiyori Studio · *in progress, not public yet*

A desktop studio for translating manga into Thai, a series at a time.
It began as a fork of [Koharu](https://github.com/mayocream/koharu) by
mayocream and grew into an app of its own.

- **The page pipeline:** text detection, OCR and inpainting on ONNX
  Runtime (GPU through DirectML, CPU as fallback), with no cloud needed
  for the images.
- **A series, not a page:** a library of chapters, a glossary, a cast
  of characters and a translation memory, so names and terms stay the
  same from chapter 1 to chapter 160.
- **Thai typesetting:** Thai line breaking from a word list, fitting
  text into balloons, and a lettering engine for Thai sound effects
  written in Rust (it also runs in the browser through WebAssembly).
- **AI as a co-worker:** an MCP server so agents like Claude or Gemini
  can translate, letter and check a chapter with the same tools I use,
  plus an AI review that suggests better wordings that fit the box.
- **Hand tools** for the last 10%: clone, heal and restore for what the
  automatic cleaning misses.

Rust · Tauri · React · TypeScript · ONNX Runtime · SQLite

### 📜 Archivist · *in progress, not public yet*

A roleplay and storytelling chat app. It started as a small JRPG you
play by talking, and became a place to talk with characters from
community character cards, one-on-one, in a group or as a whole scene,
or to play story modes like JRPG, mystery, horror and slice of life.

- **Characters that remember:** an "archivist" keeps the story as it
  goes: long-term memory, a sheet for each character, promises made in
  conversation, even a character's private diary, so they still know
  you a thousand turns later.
- **Cards as they are written:** reads the common card formats
  (SillyTavern, Chub, RisuAI), including their scripts and modules.
- **Thai and English:** Thai narration written directly by the model,
  or a translation layer for models that only write English.
- **Any model:** local models through Ollama, or Gemini and OpenRouter.

Next.js · TypeScript · SQLite · Ollama

### 🎙️ Donari · *in progress, not public yet*

A stream community manager for streamers and VTubers. It started as a
donation alert for one stream and kept growing.

- **One place for a stream:** donations and Super Chats from
  Streamlabs, YouTube and Twitch, a single live chat across platforms,
  and the same viewer recognised on each of them.
- **Alerts read aloud:** text-to-speech through Google, OpenAI or
  Gemini (which picks a voice and a tone for each message), or a Thai
  voice that runs locally.
- **On screen:** twelve OBS overlay styles, end-of-stream credits, a
  poll counted across YouTube, Twitch and Kick, and donation tiers that
  switch OBS scenes or throw items at a VTube Studio model.
- **Two ways to run:** a Windows desktop app that needs no cloud, or a
  hosted mode for a small group of streamers, each with their own data.

React · Node.js · Socket.io · SQLite · Electron · Docker

### 📱 [Kagami Cast](https://github.com/EarthWL/kagami-cast)

Mirror an iPhone or iPad to a Windows PC: a small control panel around
[UxPlay](https://github.com/FDH2/UxPlay), the open-source AirPlay
server. Quality presets, GPU decoding, optional PIN pairing, and the
picture sent straight into OBS Studio. No account, no telemetry.

C · Windows · AirPlay

---

## Other things I've built

Mostly private, kept here as a map of what I've been curious about:

- **A script runner** in Go: queueing, versioning, secrets, roles and
  logs for small Python jobs, my answer to "what if Apps Script were
  mine."
- **Thai documents:** a generator for Thai official-document layouts,
  DOCX → PDF services, and a PDF signing service (PAdES).
- **More stream toys**: a VTuber portal with a live schedule, and a
  tarot-reading web app.
- **Little utilities**: a Chrome extension that adds an ambient glow
  around YouTube and Bilibili videos, and an observability lab with
  Kong, Prometheus and Grafana.

## Curious about lately

On-device ML for images (detection, OCR, inpainting) · AI agents and
MCP · Thai typography · Rust for desktop apps

## Tools I reach for

Rust · TypeScript · Go · Python · Tauri · React · Next.js · SQLite ·
PostgreSQL · Docker

---

📫 [wanadtapong.earth@outlook.co.th](mailto:wanadtapong.earth@outlook.co.th) ·
[LinkedIn](https://linkedin.com/in/earthwl)
