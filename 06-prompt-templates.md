# AI Prompt Templates Reference

> Use these templates to generate specific HBR-style charts. Always append the **Style DNA block** from [07-style-dna.md](./07-style-dna.md) for best results.

---

## Template A: Horizontal Icon-Bar Chart
*(Based on: "Do You Send Colleagues Workslop?")*

```text
Create a data visualization in the style of Harvard Business Review Data & Visuals.
Chart type: Horizontal bar chart with pie-icon row labels.
Each row has: 
(1) a pie/donut icon on the left showing the proportion as a filled arc, 
(2) a category label, 
(3) a horizontal bar in lavender/violet (#C4A8D9), 
(4) a numeric value right-justified.
```

---

## Template B: 2×2 Strategic Matrix
*(Based on: "Framework for Gen AI")*

```text
Create a 2×2 matrix visualization in the HBR editorial style.
Layout: 4 quadrants arranged in a 2×2 grid.
X-axis label: [variable], LOW (left) to HIGH (right), in colored accent text
Y-axis label: [variable], LOW (bottom) to HIGH (top), in colored accent text
Each quadrant contains:
- Bold sans-serif header (centered, 16px, white text on colored background)
- Italic sans-serif subtitle (12px, slightly transparent)
- Bullet-point examples (centered, 11px, regular weight, dotted separators)
Color scheme: Use deep-to-light tints of HBR Purple (#7B5EA7).
```

---

## Template C: Small Multiples Sparkline Grid
*(Based on: "Consumer Interest in GLP-1s")*

```text
Create a small multiples chart in HBR editorial style.
Layout: 3 columns × 3 rows of identical mini line charts (9 panels total)
Each panel:
- Gray label/title at top, centered, sans-serif bold
- X-axis: time range, no labels shown
- Y-axis: no labels shown 
- GREEN area fill behind the trend range (light, semi-transparent)
- BOLD RED line showing the focal trend
- Red dot at the final data point
- Red numeric callout next to the final dot (e.g., "+399%")
Panel background: white with very light gray border.
```

---

## Template D: Dot Strip Plot / Cleveland Chart
*(Based on: "Human Board Performance")*

```text
Create a dot strip chart (Cleveland dot plot) in HBR editorial style.
Each row represents a category. On a shared horizontal scale, plot 3 dots:
- Teal/green dot: first series (e.g., "Group A")
- Orange dot: second series (e.g., "Group B") 
- Blue dot: third series (e.g., "Group C")
Dots connected by a thin horizontal dashed line between leftmost and rightmost dot.
Each dot labeled with its numeric value directly above/beside it.
Legend: Three colored labels at top, bold sans-serif, in series colors.
```

---

## Template E: Value-Flow / Process Illustration
*(Based on: "Why Don't Gen AI Gains Show Up in P&L?")*

```text
Create a value-flow diagram in HBR editorial style.
Concept: Show potential value being "lost" at multiple stages.
Elements:
- Thick horizontal bar at top: deep purple (#7B5EA7), labeled "Potential [Value]"
- 5 columns above bar: each with colored header and italic explanation text
- From each column: curved downward-flowing arrow in medium purple draining FROM the bar
- Bar progressively narrows to show remaining value
- At far right: thin line and label showing "Realized [Value]"
Style: Very editorial/illustrative. No grid.
```

---

## Template F: Divergence Line Chart with Shaded Gap
*(Based on: "When Productivity and Wage Growth Diverged")*

```text
Create a dual-line divergence chart in HBR editorial style.
Two time-series lines from same starting point that diverge:
- Line 1 (dominant): bold RED (#D0021B), thick stroke (~2.5px)
- Line 2 (lagging): medium GREEN (#4CAF50), thinner stroke
- Shaded area between lines: light pink/red at ~15% opacity
Annotations: Direct label on each line (e.g., "PRODUCTIVITY", "WAGES").
Dotted horizontal gridlines only.
```

---

## Template G: Labeled Lollipop-Bubble Chart
*(Based on: "What LLMs Value")*

```text
Create a horizontal lollipop-bubble chart in HBR editorial style.
Each row:
- Left: category label (sans-serif, medium gray, right-justified)
- Middle: dotted line extending right
- Right: filled circle (large, ~35px) in solid purple (#7B5EA7)
- Numeric value centered inside circle in white bold sans-serif
Rows sorted descending by value.
No axis, no gridlines.
```

---

## Template H: Scatter Positioning / Quadrant Map
*(Based on: "Human vs. AI Awareness of Car Brands")*

```text
Create a 2×2 quadrant scatter plot in HBR editorial style.
Background: four color-filled zones at 20% opacity (Teal, Amber, Lavender, Sage).
Each zone labeled centered in its accent color, italic bold.
Data points: small filled circles (~8px) labeled directly with entity name.
Axes: x and y variables, 0–100%. Axis labels at ends of axes.
Color legend below: colored dot + label + 2-sentence description per zone.
```

---

## Template I: Network / Force Graph
*(Based on: "Unexpected Connections")*

```text
Create a network graph visualization in HBR editorial style.
Nodes: 
- Large industry cluster "bubbles" (soft tints, centered labels)
- Medium labeled firm nodes (filled circles)
- Small unlabeled background nodes
Edges: 
- Thin light gray lines (background connections)
- HIGHLIGHTED FOCAL edges: thick bold red lines (#D0021B) from one selected node
Background: white. No axes.
Legend: "Thicker line = stronger connection" in italic gray.
```

---

## Template J: S-Curve / Trajectory Diagram
*(Based on: "Seven Career Stages for Salespeople")*

```text
Create an S-curve trajectory diagram in HBR editorial style.
One bold magenta/pink curved line (#E91E8C) rising bottom-left to top-right.
- 5–7 labeled node dots along the curve with stage names
- Horizontal dashed lines separating stages into labeled bands
- A BRANCH: from one mid-curve node, a dotted line branches off in different direction
Y-axis: "RESULTS" (teal accent). X-axis: "EXPERIENCE" (teal accent).
```

---

## Template K: Diverging Horizontal Bar (Sentiment)
*(Based on: "Return-to-Work Orders")*

```text
Create a diverging horizontal bar chart in HBR editorial style.
Three sentiment zones per row:
- LEFT: "Unlikely" — dark purple (#6B46A0), wider
- CENTER: "Neither" — light gray (#D0D0D0), narrow
- RIGHT: "Likely" — light lavender (#E8D5F0)
Column headers above chart at zone boundaries in matching colors.
Numeric % labels inside each segment.
Rows separated by thin light gray horizontal rules.
```

---

## Template L: Multi-Panel Infographic with Stat Cards
*(Based on: "The Eldercare Picture")*

```text
Create a multi-panel infographic in HBR editorial style.
TOP: Comparative vertical bar panel (gray and blue bars).
MIDDLE: Line chart panel showing future projection.
RIGHT: Isotype icon array (person icons showing ratio).
BOTTOM: 3-column stat cards (LARGE BOLD % at top, descriptor, donut chart).
Sections separated by thin light gray horizontal rules.
```

---

## Template M: Bubble Dot Matrix
*(Based on: "LLM Brand Mentions")*

```text
Create a bubble matrix visualization in HBR editorial style.
Grid: rows = entities, columns = categories.
Each cell: filled circle whose SIZE is proportional to value and COLOR matches column.
Column colors: Green, Amber, Blue, Purple, Gray, Orange.
Value labeled inside circle in white bold.
Column headers: bold sans-serif in column's accent color with downward arrow.
```

---

*Back to [README](./README.md)*
