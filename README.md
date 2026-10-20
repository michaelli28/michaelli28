<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:0ea5e9&height=140&section=header&text=Hi,%20I'm%20Michael&fontColor=ffffff&fontSize=42&fontAlignY=38&animation=fadeIn" alt="Hi, I'm Michael" width="100%" />

I'm a computer science student at Carnegie Mellon University (class of 2029). I mostly build apps around LLM agents, small machine learning experiments and developer tools, and I also like math. Most of my projects are TypeScript or Python.

<a href="https://www.linkedin.com/in/michael-li2"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" height="40" /></a>

## Projects

### Top projects

- **[TreeMux](https://github.com/michaelli28/treemux)** (TreeHacks 2026): Hands one task to several Claude Code agents running in Modal sandboxes. Each agent pushes its app to its own GitHub branch and Vercel deployment, then AI judges (some using a real browser) review the live sites and rank them.
- **[AT-Agent](https://github.com/michaelli28/accessibility-agent)**: A Playwright command-line tool that checks web pages for accessibility problems. It runs axe-core scans, compares the DOM with Chrome's accessibility tree to find controls screen readers can't reach, walks the page with the Tab key to find keyboard traps, and can let an LLM agent try a task while auditing. Team project.
- **[SpotifySorter](https://github.com/michaelli28/spotify-sorter)**: A local Next.js app that scans a Spotify library, has Claude propose mood categories and score every track against them in batches, then writes the results back to Spotify as private playlists. A separate `ml/` experiment trains small PyTorch models on frozen audio embeddings (MERT, CLAP) to predict Claude's picks from the audio alone.

### More projects

- **[Proteus](https://github.com/michaelli28/proteus-forecasting)**: A TypeScript simulation engine that splits a question into outcome ranges, runs a seeded ensemble of simulations of a synthetic world, and turns the share of runs in each range into probabilities. An abstention gate declines to answer when the evidence cannot tell the ranges apart. Python solvers (WNTR/EPANET, SciPy) handle the water network and repair scheduling models.
- **[Entity](https://github.com/michaelli28/entity)**: A Next.js and FastAPI app where startup founders talk with a Claude mentor in structured sessions. Each chat turn streams a reply, pulls structured facts out of the founder's answers, and can cite research paper excerpts retrieved from Postgres with pgvector.

### Hackathon and competition builds

- **[Lantern](https://github.com/michaelli28/lantern)** (Claude Hackathon 2026): Turns a WW2 veteran's YouTube testimony into a letter in their voice. A chain of Claude agents pulls story fragments out of the transcript, fact-checks them with web search, maps the people and places, and writes the letter, streaming each step to the browser.
- **[Imposture](https://github.com/michaelli28/imposture)** (YHack 2026): A webcam desk pet. MediaPipe models score posture and spot phones, an event bus turns those readings into pet reactions sent to an Arduino LCD over serial, and a wake word plus speech-to-text handles voice commands.
- **[ECHO](https://github.com/michaelli28/echo-platformer)** (TartanHacks 2026): A browser puzzle platformer in a single HTML file. A fixed 30 fps loop keeps a two-second buffer of the player's positions that a ghost copy replays, with Canvas 2D lighting and all sound generated with the Web Audio API.
- **[Carnegie Cookoff Bot](https://github.com/michaelli28/overcooker/blob/master/bots/optimal_bot.py)** (AWAP 2026): A Python bot for a two-team kitchen game. It finds paths with BFS on demand and caches the distances, ranks open orders each turn, and turns each order into a list of recipe steps that the robots carry out one at a time.

### Smaller projects

- **[Cal-CMU](https://github.com/michaelli28/cal-cmu)**: A SwiftUI iOS calorie tracker built around CMU dining menus. It talks directly to Supabase for sign-in, Postgres tables protected by row level security, and meal photo storage. Team project.
- **[Nova](https://github.com/michaelli28/nova-language-tutor)**: A role-play language tutor over a live video call. A Pipecat pipeline chains voice activity detection, Deepgram speech-to-text, an LLM through OpenRouter, ElevenLabs speech and a Tavus talking avatar, connected to a Next.js app over WebRTC.
- **[Immersion Assistant](https://github.com/michaelli28/immersion-assistant)**: A macOS prototype that takes screenshots, reads the text with Tesseract OCR, adds pinyin, and draws the result in a PySide6 overlay. The translation step is still a placeholder.

## Languages and tools

<img src="https://skillicons.dev/icons?i=ts,py,js,swift,cpp,react,nextjs,tailwind,fastapi,pytorch,postgres,supabase,docker,arduino&perline=14" alt="TypeScript, Python, JavaScript, Swift, C++, React, Next.js, Tailwind CSS, FastAPI, PyTorch, PostgreSQL, Supabase, Docker, Arduino" />

Also: Playwright, pgvector, Modal, Claude API

## GitHub activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/michaelli28/michaelli28/output/top-langs-dark.svg" />
  <img src="https://raw.githubusercontent.com/michaelli28/michaelli28/output/top-langs.svg" alt="Most used languages across my public repos" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/michaelli28/michaelli28/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/michaelli28/michaelli28/output/github-snake.svg" alt="A snake eating my GitHub contribution graph" />
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:0ea5e9&height=100&section=footer" alt="" width="100%" />
