# Design Specification: Ganesh Venkatesan Profile System

## Reference Visual & Design Inspiration

A precision, evidence-first technical editorial system tailored for **Ganesh Venkatesan**—AI Engineer specializing in **A2A (Agent-to-Agent) architectures, ADK (Agent Development Kit) frameworks, Contact Center automation, and Healthcare systems** with experience across **Thunai AI**, **Sarvam AI**, and **Zoho**.

## Design Summary

The design language balances high-velocity real-world AI engineering with rigorous architectural clarity:
- Crisp light editorial canvas (`#F8FAFC` to `#F1F5F9`) with subtle slate grid patterns and refined card boundaries.
- Vibrant, calibrated accent tokens: Deep Teal (`#087F80`), Cobalt Blue (`#2159E8`), Royal Violet (`#7254B3`), and Warm Amber (`#9A6217`).
- Clean, high-contrast typography pairing modern sans-serifs (`Inter`, `Avenir Next`, `Segoe UI`) with monospaced telemetry (`ui-monospace`, `SFMono-Regular`).
- Semantic SVG motion: orbiting telemetry signals, scanning beams, packet traces, and pulsing indicators that cleanly collapse when `prefers-reduced-motion` is active.
- Grounded claims: every metric is tied directly to verifiable GitHub repositories, DeskMate releases, LangGraph workflows, and A2A & ADK Healthcare Contact Center pipelines.

---

## Design Tokens

### Color Palette (Full Light Editorial Theme)

| Token Role | Hex Code | Visual Application |
|:--|:--|:--|
| **Canvas Background** | `#F8FAFC` → `#F1F5F9` | Crisp, editorial off-white / light-slate gradient base for cards &amp; SVGs |
| **Primary Text / Heading** | `#14253E` | Deep navy ink for high-contrast headings and prominent title elements |
| **Secondary / Muted Text**| `#526177` / `#64748B` | Slate text for descriptions, metadata, and formula denominators |
| **Direction / Triage** | `#2159E8` | Step 01 DIRECT, clinical intake, and policy boundaries (Cobalt Blue) |
| **A2A &amp; ADK Orchestration** | `#087F80` | Step 02 A2A &amp; ADK FLOW, DeskMate anchor, and live beacon signals (Deep Teal) |
| **EHR Retrieval / MCP** | `#7254B3` | Step 03 RETRIEVE, A2A Contact Center pipeline, and clinical RAG (Deep Violet) |
| **Verified Resolution** | `#9A6217` | Step 04 RESOLVE, audited handoffs, and deterministic execution (Rich Amber) |
| **Border &amp; Dividers** | `#D9E2ED` / `#E2E8F0` | Crisp 1.5px architectural panel boundaries, subtle grid tracks and card dividers |

### Typography & Hierarchy

- **Hero Headings**: `Avenir Next`, `Segoe UI`, system sans-serif (48px, weight 780, letter-spacing `-1.6px`).
- **Section Headings**: System sans-serif, bold, compact tracking.
- **System Labels & Telemetry**: `ui-monospace`, `SFMono-Regular`, `Consolas`, monospace (10–13px, uppercase, wide tracking `1.2–3.3px`).
- **Body & Explanations**: Concise, active voice focusing on reproducible code, architecture, and verifiable healthcare systems.

---

## Component Architecture

1. **Animated Hero Banner (`assets/hero.svg`)**:
   - 1200×420 responsive SVG canvas with radial glows and animated scanning beams.
   - Exact phrasing: *"I build agentic systems that can prove what happened."*
   - Kicker: `GANESH VENKATESAN / EVIDENCE-FIRST AGENTIC SYSTEMS`
   - Subtitle: `AI engineer · Agentic AI engineer · Enterprise AI`
   - Dual-loop orbital telemetry with moving data packets (`--dx`, `--dy`).
   - Center verified core featuring animated checkmark draw and pulsing beacon rings.
   - 4 State chips: `DIRECTED`, `ORCHESTRATED`, `RETRIEVED`, `EXECUTED`.

2. **Agentic Operating Model (`assets/agentic-operating-model.svg`)**:
   - 1200×520 full architecture schematic for A2A Contact Center &amp; Healthcare AI.
   - Top throughput formula: `A2A THROUGHPUT = verified clinical & contact resolutions ÷ human direction & review`.
   - 4 Sequential capability nodes: `01 TRIAGE & DIRECT`, `02 A2A & ADK FLOW`, `03 RETRIEVE`, `04 RESOLVE`.
   - Clinical & Human Authority and Evidence Gate policy foundations.

3. **Active Systems Showcase (`assets/building-now.svg`)**:
   - 1200×410 asymmetric anchor-plus-rotating-ledger layout.
   - Two strategic pillars: **DeskMate** (Local AI Desktop Copilot) and **A2A Contact Center & Healthcare AI**.
   - 6 Auto-ranked public frontier projects cycling every 8 seconds: DeskMate, LangGraph_ArgoCD, agent-runtime, VerdexAI, A2A & ADK Core, and Developer Portfolio.

4. **Latest Verified Work (`assets/latest-verified-work.svg`)**:
   - 1200×365 vertical pulse timeline tracking latest merged DeskMate PRs, desktop releases, and A2A & ADK agent architectures.
   - Side-rail quantitative counters: 105+ Repositories, 17+ PRs, 100% Offline Capability.

---

## Operating & Content Principles

- **Ship verifiable systems**: Demos and architecture diagrams must reflect real code and runnable pipelines.
- **Ground every clinical action**: Retrieval-augmented generation and tool calling over unverified model speculation.
- **Inspectable proof**: Keep repository receipts, PR records, and installation instructions open and reproducible.
