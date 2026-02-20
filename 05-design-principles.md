# Design Principles & Techniques

> The HBR editorial visualization philosophy distilled into actionable principles.

---

## Core Principles (Original)

### A. Narrative-First
Every chart has a **declarative title that states the conclusion**, not just the variable.
- Example: "Low Employee Engagement Across the Globe" (not "Employee Engagement by Region")
- The subtitle adds one sentence of interpretive framing
- The data supports the argument; it does not merely display information

### B. Show the "Missing" Data
The **ghost bar technique** (pale bar to 100% behind a bold bar) is used consistently to show what's NOT happening — the context that makes the data meaningful.
- Engaged employees at 23%? Show the 77% ghost behind it
- This technique makes the insight visceral without adding more data

### C. Layered Encoding
Multiple visual variables are layered simultaneously:
- Bar charts encode both **position AND a ghost reference**
- Bubble/Gantt charts encode **time (x), category (y), and scale (bubble size)**
- Pie-icon rows encode **row identity AND proportion** simultaneously
- More dimensions of data, same chart real estate

### D. Small Multiples for Comparison
When comparing across categories over time, HBR uses a **3×3 or 3×4 grid** of identical mini-charts:
- Same axes and scale across all panels
- Each panel labeled at top
- Bold end-value callout (e.g., "+399%")
- Green area fill + bold red trend line per panel

### E. Annotation > Legend
**Direct labels** on data elements replace traditional legends wherever possible:
- "PRODUCTIVITY" is labeled directly on the line
- "Trust senior leaders / Do not trust" appears below bars
- Eliminates the visual lookup cost of a separated legend

### F. Minimal Grid
- **Horizontal dotted lines only** (never vertical)
- Very sparse: typically 4–5 gridlines maximum
- No axis borders or box frames
- White space does the heavy lifting

### G. Conceptual/Process Charts Use Illustration
Non-quantitative frameworks are **illustrated with shapes and arrows** rather than text tables:
- 2×2 matrices, flowcharts, value-drain diagrams
- The P&L value leakage chart with curved drain arrows is data visualization as editorial illustration
- These are not data charts — they are information design

---

## Advanced Techniques (Extended)

### H. The Accent Axis Technique
Every HBR conceptual chart labels its axes in a **colored accent** (teal, purple, or amber), separate from the black/gray body text.
- Creates a visual hierarchy: "this is the organizing logic"
- Axis label often includes an italic sub-question
- Example: "Do we have the capacity, resources, and timeline to execute effectively?"

### I. Monochromatic Matrix Tinting
2×2 matrices frequently use **one hue in 4 tints** (darkest = highest value quadrant, lightest = lowest):
- Communicates spectrum without visual noise
- Avoids the multi-color confusion of 4 different hues
- One accent color family, 4 distinct stops

### J. Inline Colored Text for Emphasis
Inside chart bodies:
- Selected words or phrases are **colored in the accent color** while surrounding text remains black or gray
- Creates editorial emphasis without bolding entire blocks
- Used especially in tables and 2×2 matrices

### K. Comparison Tables Always Highlight the "Hero" Column
In any comparison table (3+ columns):
- The **featured/recommended column** gets a solid background tint (lavender, teal)
- Other columns stay white
- Only the highlighted column uses italic text throughout

### L. The "Bad Example" as Pedagogy
HBR occasionally shows a **"wrong way" visual** — deliberately cluttered, radial, low-hierarchy — followed by the correct version:
- Teaches by contrast
- The hub-and-spoke/radial diagram is HBR's canonical "do not use" example
- Reference: "Avoid radial/hub-spoke layouts; use a horizontally-oriented 2×2 or ranked bar instead"

### M. High-Frequency Data Uses Dense Line Charts
For economic or daily data:
- **Unsmoothed, full-resolution spiky line** (not a moving average)
- Emphasizes volatility itself as the message
- One bold color on pure white with only dotted gridlines
- No smoothing, no moving averages — the noise is the story

---

## Anti-Patterns to Avoid

| Anti-Pattern | Why HBR Avoids It |
|--------------|--------------------|
| Radial / hub-and-spoke diagrams | Low data density, hard to compare values |
| 3D charts of any kind | Distorts proportions, adds no information |
| Gradients or drop shadows | Visual noise without meaning |
| Rainbow color schemes | No semantic meaning, visually jarring |
| Separate legend boxes | Forces lookup; direct labels are more efficient |
| Descriptive (not declarative) titles | Misses the opportunity to convey insight |
| Vertical gridlines | Clutters the reading direction of the data |
| Chart border frames | Unnecessary containers; white space suffices |
| More than 3 colors per chart | Loses focus; each color should carry meaning |

---

*Back to [README](./README.md)*
