# AI Architect Studio - Floor Plan Agent

**Mission**: Create the best specialized AI Architect Agent for conceptual floor plan design, capable of substituting junior architects in a professional studio.

## Focus
- Delhi / NCR residential builder floors
- 3BHK typical floor plans
- Vastu integration (practical, not rigid)
- Space planning, circulation, ergonomics, proportions, volume & feel
- Bylaws compliance (setbacks, light, ventilation)
- Human-habitable, non-hallucinated designs

## Exam Criteria (Benchmark)
Plot: 30 ft width × 60 ft depth (1800 sq ft), North-facing, New Delhi (Ajpan Nagar type).
- Front setback: 10 ft (North)
- Front road: 20 ft, Rear service road: 20 ft
- Stilt parking + Upper Ground / 1st / 2nd / 3rd floors (typical 3BHK)
- Requirements: 3 Bedrooms + 3 attached Bathrooms (min 5'-0" × 8'-6"), Living + Dining (grand entrance feel), Kitchen with natural light
- Vastu: One bedroom (preferably Master) in SW; no bedrooms in NE; Kitchen preferably SE; max natural light for Kitchen + all BRs via large sliding windows (9' lintel); shafts OK for baths
- Core: Efficient Staircase + Elevator with common landing, minimal footprint
- Output required: **3 distinct conceptual floor plan options**
- Jury (Human Architect) scores each. Agent must score ≥7/10 to pass.

## Status
Agent is being built autonomously. Floor plan options for the exam are under preparation and will be published in `/exam-results/`.

## Architecture Knowledge Base
Agent draws from:
- Global architectural principles (space planning, proportion systems, circulation diagrams)
- Indian Vastu (practical application for North-facing)
- Delhi UBBL / MPD setbacks, FAR, coverage, stilt rules
- Ergonomics (door clearances, furniture zones, human movement)
- Professional drafting logic (no random boxes, no blocked doors, no impossible bathroom sizes)

## Next
Exam results with 3 options + self-critique will be added shortly.
