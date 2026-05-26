---
name: case-study-writer
description: "Write and publish B2B case studies for HVAC/commercial service businesses. Problem-solution-results framework, SEO-optimized, interview-driven."
allowed-tools:
  - write
  - edit
  - web_search
  - web_fetch
  - browser
  - exec
  - message
  - wordpress-poster
user-invocable: true
---

# Case Study Writer

Write B2B case studies for HVAC clients transitioning from residential to commercial. Use the **problem → solution → results** framework.

## Framework

Every case study follows:

```
[Client Name] had a problem with [specific HVAC pain point].
We installed/retrofitted [solution].
Results: [quantifiable outcome: energy savings %, downtime reduction, cost savings $].
```

## Structure

| Section | Content | Length |
|---------|---------|--------|
| **Title** | "How [Client] Solved [Problem] with [Solution]" | 8-12 words |
| **Executive Summary** | TL;DR: client, problem, solution, result | 3-5 sentences |
| **The Challenge** | Before-state: pain points, failed attempts, urgency | 200-300 words |
| **The Solution** | What was installed, why chosen, implementation process | 300-400 words |
| **The Results** | Data: kWh saved, downtime eliminated, ROI, testimonial | 200-300 words |
| **Key Takeaways** | Lessons for similar commercial clients | 100-150 words |
| **CTA** | "Need commercial HVAC solutions? Contact us." | 1-2 lines |

## Writing Rules

- First-person client quotes where possible ("We were losing 15% efficiency every quarter")
- Numbers everywhere: % reductions, $ savings, tonnage, sq ft
- Before/after comparison tables when data exists
- Avoid jargon — facility managers read these, not engineers
- SEO keywords: commercial hvac [city], hvac retrofit, [system type] installation
- End every case with a testimonial blockquote from the client

## Publishing (WordPress)

Use the wordpress-poster skill to publish on airsolutionsmechanical.ca:

```bash
python3 ~/.openclaw/workspace/skills/wordpress-poster/scripts/wp_poster.py create airsolutions "Title" -c "<html>" --status publish
```

1. Draft first → send to review
2. Add featured image (equipment photo or branded graphic)
3. Set category: "Case Studies"
4. Add tags: commercial hvac, [city], [system type]
5. Publish only after approval

## Interview Prompts (for client discovery call)

Ask the client:
1. What was breaking/generating complaints before?
2. How much were you spending on emergency repairs?
3. What made you pick us over competitors?
4. What's different now that the system is running?
5. Can you put a dollar figure on the improvement?

## Sources of Case Study Material

- Service tickets (before: repeat visits vs after: zero callbacks)
- Energy bills (before/after comparison)
- Equipment specs (what was removed vs what was installed)
- Client emails/testimonials
- Photos from install (messy old system vs clean new install)
