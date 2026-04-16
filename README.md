# Tony Frasca

**Business systems architect who builds with AI.**

18 years designing operational systems, data architectures, and process automation. Now using AI to build things that weren't possible a year ago — not toy demos, but real systems running in production and solving real problems.

### What I'm Building

**[Cortex](https://github.com/anfrasca/cortex-wiki)** — An LLM-maintained personal wiki with a first-class reliability layer. Three-layer architecture (human-owned sources, LLM-owned wiki, co-evolved schema), two-phase compile, and a named Reliability Layer: per-phase model routing (Haiku for extraction, Sonnet for generation), quiet-failure detection that blocks commits and surfaces anomalies at next session start, and a structured audit log tracking every model call with cost attribution. Inspired by Karpathy's LLM wiki concept — adopted his append-only source layer and two-phase compile, then went further with reliability infrastructure, human-in-the-loop approval routing, and operator-session knowledge capture. The repo includes a synthetic sample vault you can compile yourself to see the full pipeline fire.

**[PoolGuard](https://github.com/anfrasca/poolguard)** — An AI-powered pool safety monitor that watches my backyard camera and alerts my phone when someone is in or near the water unsupervised. Built with Claude Code, YOLO computer vision, and Unifi Protect. Shipped v1, watched it fail in the real world, diagnosed why, and redesigned v2 from the lessons learned. Running in production right now, protecting my family.

**[Parten Ranch Guide](https://github.com/anfrasca/parten-ranch-guide)** — My HOA's architectural review process was inconsistent and opaque. Neighbors were getting denied for rules that didn't exist. I downloaded every governing document, had AI extract and cross-reference them against Texas property code and local ordinances, and built a searchable reference guide. Shared it with the neighborhood — went from a frustration to a resource in about an hour.

### What I Bring

I don't write code. I design systems, define problems, make product decisions, and use AI to execute at a speed and quality that used to require a dev team. The value isn't in the code — it's in knowing what to build, why, and how to iterate when the first version isn't right.

**Background:** Salesforce platform architecture, RevOps, process automation. Built and rebuilt operational systems through two acquisitions. Once replaced a ~$900K Salesforce consulting engagement by doing the org rebuild myself in 60 days.

**Get in touch:** [LinkedIn](https://linkedin.com/in/tonyfrasca) · anfrasca@gmail.com
