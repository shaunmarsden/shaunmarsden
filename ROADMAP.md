# Roadmap

One roadmap across everything here, rather than a separate one per repo. It covers three things: [Practical AI Sales Workflows](https://github.com/shaunmarsden/practical-ai-sales-workflows), the [Sibling Projects](https://github.com/shaunmarsden/sibling-projects) family of eighteen generalised tools, and the commercial-teams family ([AI for Commercial Teams](https://github.com/shaunmarsden/ai-for-commercial-teams), [Sales Conversation Gym](https://github.com/shaunmarsden/sales-conversation-gym), [Sales Proof Bench](https://github.com/shaunmarsden/sales-proof-bench), [Sales Value Workshop](https://github.com/shaunmarsden/sales-value-workshop)).

Each repo keeps its own detailed roadmap where one exists. This page is the short version, organised by the kind of work each item actually is: making something already built easier to adopt, testing something that has not been tried by a real independent user yet, deepening something the evidence already supports, maintaining something that is in good shape as is, or exploring something genuinely new later.

A portfolio-wide audit on 3 August 2026 confirmed 25 public repos, all active, none archived, and refreshed this page against what is actually in each one. A follow-up readability and adoption pass on 4 August 2026 looked specifically at whether a busy, non-technical salesperson can find, understand and try what is here, and added the findings below. Nothing on this page is a delivery date.

## Make Existing Work Easier To Adopt

- **Surface the interactive picker properly.** It is the easiest way for a non-technical visitor to find the right sibling tool, but it is currently linked only from inside ROUTER.md, not from the `sibling-projects` README or from any tool's own "Part of a Family" footer.
- **Give every SKILL.md file the same short copy-and-paste instructions**: where to find the raw file, what to do with the front matter at the top, and a line making clear that nothing needs installing. Right now this is assumed knowledge across all eighteen sibling tools, the sales repo and `book-to-skill`.
- **Cross-link the two sales clusters.** Practical AI Sales Workflows and the four commercial-teams repos currently do not link to each other in either direction. A visitor to one cannot discover the other without already knowing to look. This is the single cheapest, highest-value fix found in the audit.
- **Replace the commercial-teams family's shared "Part of a Family" sentence** (currently one 60-word run-on sentence, identical in all four repos) with something that actually says which one to open first, and merge `ai-for-commercial-teams`'s two near-duplicate start tables (its README and `START-HERE.md` both list almost the same four routes).
- **Disambiguate two pairs that read as more similar than they are.** In the Sibling Projects family, Claims vs Evidence Checker (checks a tracked status against the evidence held) and Evidence-Labelled Meeting Notes (the one that actually keeps confirmed facts, estimates, second-hand claims, inferences and unknowns visibly separate) sound like they do the same job by name alone; a short "not this one, try the other" line in each README would fix it. The same applies to First Contact That Isn't Generic (no existing template) and Personalise, Don't Templatise (a template already exists).
- **Fix the one structural gap found.** Diagnose Before You Respond is missing the blank template file every other sibling tool ships with.

## Test Existing Work

- **Every repo in the portfolio is still waiting on its first independent, non-builder use.** The feedback form and Discussions link on the sales repo have not been used by anyone yet, and the same is true across all eighteen sibling tools and the whole commercial-teams family. That is a bigger gap right now than anything a new feature would close.
- **Four Practical AI Sales Workflows jobs still lack a logged real-work test**, not three: handing over an opportunity, moving a stalled decision, and reviewing an outbound campaign have no real-use test logged at all; preparing for a sales call has been used live, but that use was never formally logged, so it does not belong in the same column as the twelve jobs that do have one.
- **Before Sales Proof Bench adds its next comparison type**, it should acknowledge and build on the cross-model comparison Practical AI Sales Workflows already ran and scored, rather than repeat the same case type as if it were new ground.

## Deepen Work The Evidence Already Supports

- **Sales Conversation Gym's AI-plays-the-buyer mode** is still a roadmap line, not a built prompt. It is the one genuinely new mechanic the commercial-teams family adds beyond the sales repo (live rehearsal rather than document drafting), and worth finishing.
- **Sales Value Workshop's next case** should be the enterprise or procurement-gated one already on its own roadmap. It tests a harder, more realistic "not yet" outcome than the two cases it has today, which is the right kind of addition, not just a renamed repeat.

## Maintain

- Practical AI Sales Workflows' methodology, evidence matrix and governance docs are in good shape and do not need more scope, only the real-work tests above.
- The Sibling Projects router is accurate: all eighteen linked tools exist and match their descriptions, and no broken links were found in this audit.
- Most of the eighteen sibling tools are complete and internally consistent as built. They need the disambiguation fixes above and real use, not more building.
- `book-to-skill` is complete as built: treat it as maintenance, not an expansion target.

## Explore Later, Deliberately Not Yet

These are not forgotten, they are genuinely on hold, most waiting on something specific rather than just priority.

- **Sibling repos for finance, HR or operations.** The plan was always to find a genuine practitioner from that function to co-drive it, not build it solo by analogy the way the sales repo works because it is tested against real deals. No practitioner has been found. Not being actively pursued until one is.
- **BVA and workshop-style enterprise content.** This reads as AiCore-flavoured methodology rather than generic, small-business-friendly advice. May need to stay private, or get a proper generalisation pass, before it is worth publishing.
- **A portfolio map diagram, considered and set aside for now.** The readability pass looked at whether the profile README needs one showing how the three families relate. Its conclusion: a visitor's real question is "which of these fits my problem, and has it been tested", which a short table answers better than a family-tree image would. Revisit only if a future check finds people still can't navigate with the table and the cross-links above in place.
- **A proper visuals and short-video pass** for the sales repo, beyond the diagrams already in place. Flagged before as needing a genuinely concentrated session rather than a few minutes here and there.
- **Better, more natural voices for the interactive demo.** Blocked on either generating the audio files directly or sharing an API key with billing attached; the current browser voice reads as dated.
- **An n8n worked example** inside the sales repo's own automation guide, as one honest example of a repeatable, approval-gated workflow, not a new headline tool.
- **New fictional sibling-tool cases that only change the names in an existing pattern.** The audit found none of these are needed right now; every existing case still earns its place.

## A Few Rules for Using This Page

- Keep facts, estimates and assumptions clearly separate, including on this page: nothing here is a delivery date.
- Add to "Explore Later" freely. Only move something up when it is actually being worked on.
- If a "Later" item stays parked for good, say so plainly and remove it, rather than let this page collect ideas nobody intends to build.
- Repository content and commit activity are not evidence of adoption. Internal use is not independent validation. This page tracks work, not proof.
