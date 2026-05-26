# Figure source — Exploratory Report

These are the schematic sources for Figures 1–3. They render directly on GitHub (Mermaid).
**Production note:** EMBO Reports requires figures as vector/high-resolution raster (PDF/EPS, or TIFF at ≥300 ppi). Before submission, export each diagram to a clean vector schematic (e.g., redraw in Illustrator/Inkscape or render Mermaid to SVG → PDF). The existing repository PNGs (`figures/fig1–3`) depict the broader mtDAMP→disease overview and do **not** depict the v0.3 spine — they should not be used as the submission figures without redrawing.

---

## Figure 1 — From binary gate to disclosure surface

```mermaid
graph TD
    subgraph A [Textbook model: the binary gate]
        direction LR
        H[Healthy<br/>sealed wrapper] -->|rupture| D[Apoptotic<br/>terminal state]
    end
    subgraph B [Proposed model: the disclosure surface]
        direction LR
        S1[1. Exchange<br/>metabolites] --> S2[2. Strain<br/>lipid asymmetry]
        S2 --> S3[3. Alarm<br/>mtDNA leak]
        S3 --> S4[4. Commitment<br/>BAX/BAK MOMP]
    end
    A ~~~ B
```

## Figure 2 — The sequential-sensitization spine

```mermaid
sequenceDiagram
    participant S as Stress amplitude
    participant V as VDAC1 state
    participant B as Bcl-xL / BAX network
    participant C as Cellular outcome
    S->>V: increasing stress & lipid changes
    V->>V: 1. oligomerization (trimers/tetramers)
    V->>C: 2. sublethal leak (mtDNA -> cGAS-STING)
    S->>V: sustained stress (sensitization threshold)
    V->>V: 3. N-terminal helix exposure to cytosol
    V->>B: 4. VDAC1-N binds Bcl-xL BH3 groove
    B->>B: 5. Bcl-xL neutralized -> BAX/BAK derepressed
    B->>C: 6. macropore formation (cytochrome c release)
```

## Figure 3 — Predicted temporal ordering (titration / timecourse)

```mermaid
gantt
    title Predicted temporal ordering
    dateFormat X
    axisFormat %s
    section Upstream sensitization
    VDAC1 oligomerization       :a1, 0, 30
    VDAC1 N-terminal exposure    :a2, 20, 60
    section Alarm cargo
    Cytosolic mtDNA (short)      :a3, 10, 50
    cGAS-STING activation        :a4, 15, 60
    section The threshold
    VDAC1-N / Bcl-xL binding     :crit, a5, 30, 70
    section Terminal commitment
    BAX/BAK activation           :a6, 40, 80
    Cytochrome c / MOMP          :a7, 50, 90
```
