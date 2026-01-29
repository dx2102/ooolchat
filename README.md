# OoolChat

### Try the app online: https://dx2102.github.io/ooolchat/

This is a simple web app to call LLM APIs. 

It aims to create a clean and fast UI baseline, while remaining a single-HTML file with vanilla JS.

Simply paste the code into LLMs to safety-check/customize it.

Main Goals:
- Concise, single-file code
- Easy to customize with LLMs or check for safety
- Design:
  - Consistent layout and color (tailwind)
  - Readable, high-contrast text

---

## Todos:

### 1. Basics
- [x] Streaming output
- [x] Multi-line input bar

### 2. Better Markdown
- [x] Markdown rendering (markdown-it)
- [x] Code highlighting (highlight.js)
- [x] Math rendering (katex)

### 3. Better Utilities
- [x] Store chat history locally (IndexedDB)
- [x] Search bar
- [ ] WebWorker full text search
- [ ] Resize / Hide sidebar
- [ ] Responsive UI / Phone support

### 4. Even Better Utilities
- [x] CDN library caching
- [x] Load large libraries in the background
- [x] Auto-scrolling (disabled by default)
- [x] Auto-focus
- [x] Scroll chaining
- [ ] Memorize scrolling position
- [ ] Command+Click for a new window

### 5. Even Better Markdown
- [x] Copy button
- [x] Correct LaTeX Copying
- [x] Markdown tables
- [ ] Support the checklist syntax
- [x] Skip CJK "Enter" button in input box 
- [x] Fix CJK characters bolding in markdown

### 6. Chat management
- [ ] Delete / Pin / Rename chat
- [ ] Stop generation
- [ ] Edit message
- [ ] Retry
- [ ] Branching
- [ ] Allow parallel generation

### 7. Settings / Customization
- [x] Change API Keys
- [ ] Manage models (api keys, base url, system prompts, temperature, top_p, max_tokens)
- [ ] Manage appearance (font, color, padding, darkmode preset)
- [ ] Slash commands
- [ ] Shortcut keys
- [ ] Export data
- [ ] Delete all images

### 8. Advanced usage
- [ ] List and jump to messages
- [ ] Metadata (pricing, token count, raw json)
- [ ] Image uploads
- [ ] Show thinking trace
- [ ] Code Execution (WebAssembly)
- [ ] SVG / Mermaid rendering
- [ ] Print page
