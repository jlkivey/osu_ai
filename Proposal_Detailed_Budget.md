# Detailed Budget Breakdown

All figures are FY‑based; totals shown as a range to reflect the $1–2 M estimate.

| Category | FY 2026‑27 | FY 2027‑28 | FY 2028‑29 | FY 2029‑30 | FY 2030‑31 | Subtotal (5 yr) |
|----------|------------|-----------|-----------|-----------|-----------|----------------|
| **Personnel** (PI, Co‑PIs, staff salaries & benefits) | $150k–$250k | $200k–$300k | $200k–$300k | $180k–$260k | $160k–$240k | $890k–$1.35M |
| **AI Consultant** (contracted development, 0.5 FTE) | $20k–$28k | $20k–$28k | $20k–$28k | $20k–$28k | $20k–$28k | $100k–$140k |
| **Subaward – Grow Next Gen** (host platform, licensing) | $30k–$50k | $40k–$60k | $40k–$60k | $35k–$55k | $30k–$45k | $175k–$280k |
| **Travel & Participant Support** (workshop travel, stipends) | $20k–$35k | $25k–$40k | $25k–$40k | $20k–$35k | $15k–$30k | $105k–$180k |
| **Supplies & Equipment** (see detailed breakdown below) | $45k–$70k | $35k–$60k | $35k–$60k | $30k–$55k | $25k–$45k | $170k–$290k |
| **Cloud Infrastructure** (GPU/CPU compute, storage, APIs) | $35k–$60k | $30k–$50k | $28k–$48k | $25k–$45k | $22k–$40k | $140k–$243k |
| **Vector Database & MLOps** | $6k–$10k | $6k–$10k | $6k–$10k | $6k–$10k | $6k–$10k | $30k–$50k |
| **LLM API Credits** (ChatGPT, Gemini, Grok) | $18k–$30k | $15k–$25k | $14k–$24k | $12k–$22k | $10k–$20k | $70k–$111k |
| **Indirect Costs** (30 % of Modified Total Direct Costs) | $145k–$250k | $169.5k–$285k | $167.4k–$283k | $150.9k–$267.4k | $138.15k–$249.1k | $771k–$1.335M |
| **Total FY‑Based** | **$470k–$823k** | **$516.5k–$890k** | **$510.4k–$883k** | **$464.9k–$817.4k** | **$390.15k–$685.1k** | **$2.35M–$3.49M** |

> **Note:** The FY totals exceed the $1‑2 M range because they include a 30 % indirect cost rate on the *modified* direct costs (the standard university rate). If the sponsor caps total award at $2 M, the indirect rate will be applied to the allowable direct‑cost ceiling, resulting in an adjusted direct‑cost envelope of roughly **$1.5 M** and indirects of **~$0.45 M**, keeping the overall award within the requested range.

### Personnel Cost Assumptions
- PI effort: 10 % FTE each year; Co‑PI(s): 5 % each.
- Graduate assistants: 0.25 FTE (salary $35k/yr) + benefits.
- Staff support (project manager, curriculum developer): 0.75 FTE total.

### Consultant Cost Assumptions
- Fixed‑price contract for AI module design, prompt engineering workshops, and RAG pipeline development.
- Rate: $125–$175 /hr; estimated 800 hrs over 5 yr.
- We have reached out to consultants available to do the project and this is the price range we have found.

### Subaward Assumptions
- Platform licensing (Grow Next Gen) – $10k/yr plus implementation services.
- Contingency for alternative Canvas delivery ($15k/yr).

### Supplied & Equipment Breakdown (2000 users over 5 years)

| Item | Qty | Unit Cost | Total |
|------|-----|-----------|-------|
| **Development Laptops** (for team/instructors) | 10 | $2,500 | $25k |
| **Shared Workshop Laptops** (Chromebooks/low-cost) | 50 | $400 | $20k |
| **Smartphones** (for Vision AI testing) | 20 | $600 | $12k |
| **Field Imaging Kit** (macro lenses, lighting, tripods) | 1 set | $8k | $8k |
| **On-Prem GPU Workstations** (RTX 4090, for demos/training) | 2 | $7k | $14k |

**Total Hardware/Equipment: ~$79k (spread across 5 years)**

### Cloud Infrastructure Breakdown

| Component | Monthly Cost | Annual | Notes |
|-----------|--------------|--------|-------|
| GPU compute (AWS P4/P5 for Vision AI training) | $1,200 | $14.4k | Burst usage during model development |
| CPU compute (APIs, RAG, web apps) | $450 | $5.4k | Always-on services |
| Storage (datasets, models, documents) | $250 | $3k | ~10–20 TB over time |
| Networking / misc | $200 | $2.4k | Data transfer, load balancers |
| **Cloud Subtotal** | ~$2,100 | **~$25.2k/yr** | |

### LLM API Credits Breakdown (2000 users)

| Service | Monthly Queries | Cost/Month | Notes |
|---------|-----------------|------------|-------|
| OpenAI API (GPT-4.1) | 20k–30k | $1,500 | Primary LLM for "Ask the Expert" |
| Google Gemini API | 10k–15k | $500 | Comparison and fallback |
| xAI Grok API | 5k–10k | $300 | Optional for comparison |
| Open-source models (Hugging Face) | Variable | $200–$300 | Self-hosted or API credits |

**Total LLM APIs: ~$2,500–$3,000/month → $140k–$180k over 5 years**

### Vector Database & MLOps

| Component | Cost/Year |
|-----------|-----------|
| Pinecone/Weaviate (RAG vector DB) | $6k |
| Weights & Biases / MLflow | $2.4k (200/month) |
| Dataset labeling tools | $10k |
| Backup & archival storage | $1.2k |

**Total: ~$20k–$30k over 5 years**

### Learning Management Systems

| Platform | Cost/Year |
|----------|-----------|
| Canvas (ScarletCanvas) licensing + hosting | $15k |
| Grow Next Gen licensing | $10k–$12k |

**Total LMS: ~$75k over 5 years**

### Jupyter Platforms

| Option | Cost/Year |
|--------|-----------|
| Google Colab Pro / JupyterHub hosting | $6k (500/month) |

**Total: ~$30k over 5 years**

### Key Cost Insights

1. **AI usage is NOT the dominant cost** - Infrastructure + LMS + data work = majority
2. **Scales well to 2,000 users** - Cloud + API model avoids linear hardware scaling
3. **Cost reduction options available** - More open-source models, university infrastructure

---

*Budget prepared: April 6, 2026*
