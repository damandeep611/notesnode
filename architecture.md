Tech Breakdown (Konva.js path)

Core (Week 1–2):
Canvas with pan/zoom.
Add text boxes, sticky notes, rectangles, arrows.
Grouping + dragging.
Save/load board (localStorage → Postgres later).


Phase 2 (Week 3+):
Add right-click/toolbar option → “Ask AI about this note.”
Send note content → Gemini/OpenAI → create AI response node connected to it.
Keep AI replies visually distinct (e.g., glow border, different color).

Polish (Week 4+):
Framer Motion animations (notes pop in, arrows animate).
Themes (whiteboard mode, dark cyber mode).
Export board as PNG/Markdown



 basically saying:

Phase 1 → Excalidraw clone (notes + sketches)
Users drop sticky notes, doodles, boxes, arrows.
Focus is on note-taking & idea capture (low barrier).
Konva.js shines here because you can do freeform shapes, sticky notes, pens, arrows, text blocks easily.

Phase 2 → RabbitHole-style AI integration
Once notes exist, user can highlight/select a note → “search related” → spawn AI node(s).
This turns static notes → dynamic knowledge graph.
Fits beautifully with your “write first, explore later” philosophy.