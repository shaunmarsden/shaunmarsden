# Roadmap

One roadmap across everything here, rather than a separate one per repo. It covers [Practical AI Sales Workflows](https://github.com/shaunmarsden/practical-ai-sales-workflows), the [Sibling Projects](https://github.com/shaunmarsden/sibling-projects) family of eighteen generalised tools, the commercial-teams family ([AI for Commercial Teams](https://github.com/shaunmarsden/ai-for-commercial-teams), [Sales Conversation Gym](https://github.com/shaunmarsden/sales-conversation-gym), [Sales Proof Bench](https://github.com/shaunmarsden/sales-proof-bench), [Sales Value Workshop](https://github.com/shaunmarsden/sales-value-workshop)), and two newer, standalone additions that sit outside those three families: [Practical AI Adoption](https://github.com/shaunmarsden/practical-ai-adoption), general AI-literacy guides for anyone at work, not sales-specific, and [Commercial Career Pivot Workbench](https://github.com/shaunmarsden/commercial-career-pivot-workbench), an evidence-checked career-pivot workflow for sales and commercial professionals.

Each repo keeps its own detailed roadmap where one exists. This page is the short version, organised by the kind of work each item actually is: making something already built easier to adopt, testing something with no logged independent use yet, finishing bounded work already justified by its own scope, maintaining something that is in good shape as is, or exploring something genuinely new later.

A portfolio-wide audit on 3 August 2026 confirmed 25 public source repositories, none archived, all using `main` as their default branch, and refreshed this page against what is actually in each one. A follow-up readability and adoption pass on 4 August 2026 looked specifically at whether a busy, non-technical salesperson can find, understand and try what is here, and added the findings below. Two further repositories, Practical AI Adoption and Commercial Career Pivot Workbench, were added afterward and were not part of that original count or three-family description; the portfolio now stands at 27 public source repositories. Nothing on this page is a delivery date.

## Make Existing Work Easier To Adopt

Nothing outstanding right now. Two rounds have shipped: the readability and adoption pass on 4 August 2026 found six fixes (SKILL.md copy-paste instructions, the picker's visibility, the ROUTER.md regression, the commercial-teams cross-link, two sibling-tool disambiguation notes, and the missing template file), and a follow-up sweep across all eighteen sibling tools found and fixed three more naming-confused pairs (Skill Author and Book to Skill, Make the Case and Brief Your Advocate, What's Actually Causing This Delay and Post-Mortem Builder) plus a scope gap in the Sibling Projects picker itself, which only ever covered six of the eighteen tools without saying so, and left no way back to the rest when a visitor's situation was not one of those six.

## Test Existing Work

- **No repository in the portfolio currently has a logged independent, non-builder use.** The feedback form and Discussions link on the sales repo show no logged activity yet, and the same is true across all eighteen sibling tools and the whole commercial-teams family. That is a bigger gap right now than anything a new feature would close.
- **Only one Practical AI Sales Workflows job still has no recorded real use**: reviewing an outbound campaign. Fourteen jobs have a logged real-use test, one of them a boundary finding that correctly stopped a stalled-decision case rather than proving the method can move a genuinely indecisive buyer, and Prepare for a Sales Call has been used live but not formally logged, a middle category of its own rather than a second job with no real use.
- **Before Sales Proof Bench adds its next comparison type**, it should acknowledge and build on the cross-model comparison Practical AI Sales Workflows already ran and scored, rather than repeat the same case type as if it were new ground.
- **Practical AI Sales Workflows' new approval-gated sales-copilot method has no independent test yet.** [The guide, template, fictional test and evaluation](https://github.com/shaunmarsden/practical-ai-sales-workflows/blob/main/guides/build-an-approval-gated-sales-copilot.md) are public; the builder reports internal use of a private version, but that private configuration has not been independently verified, only the public method has been. The next useful evidence is a sanitised live-run finding or an independent attempt, not more command modes.

## Finish Bounded Work Already Justified

Nothing outstanding right now. Both items here have shipped: Sales Conversation Gym's AI-plays-the-buyer mode is now a built prompt (`guides/ai-plays-the-buyer.md`), the one genuinely new mechanic the commercial-teams family adds beyond the sales repo, and Sales Value Workshop's enterprise case tests a harder, distinct "not yet" outcome, a security and procurement gate rather than the existing case's missing-owner gap.

## Maintain

- Practical AI Sales Workflows' methodology, evidence matrix and governance docs are in good shape and do not need more scope, only the real-work tests above.
- The Sibling Projects router is accurate: all eighteen linked tools exist and match their descriptions, and no broken links were found in this audit.
- Most of the eighteen sibling tools are complete and internally consistent as built. They need the disambiguation fixes above and real use, not more building.
- `book-to-skill` is complete as built: treat it as maintenance, not an expansion target.

## Explore Later, Deliberately Not Yet

These are not forgotten, they are genuinely on hold, most waiting on something specific rather than just priority.

- **Sibling repos for finance, HR or operations.** The plan was always to find a genuine practitioner from that function to co-drive it, not build it solo by analogy the way the sales repo works because it is tested against real deals. No practitioner has been found. Not being actively pursued until one is.
- **BVA and workshop-style enterprise content.** This reads as AiCore-flavoured methodology rather than generic, small-business-friendly advice. May need to stay private, or get a proper generalisation pass, before it is worth publishing.
- **A portfolio map diagram, considered and set aside for now.** The readability pass looked at whether the profile README needs one showing how the three families relate. Its conclusion: a visitor's real question is "which of these fits my problem", which a plain linked list of jobs answers better than a family-tree image would. Whether something has been tested is answered separately by the evidence-status matrix link, not folded into that list. Revisit the diagram only if a future check finds people still can't navigate with the cross-links above in place.
- **A proper visuals and short-video pass** for the sales repo, beyond the diagrams already in place. Flagged before as needing a genuinely concentrated session rather than a few minutes here and there.
- **Better, more natural voices for the interactive demo.** Blocked on either generating the audio files directly or sharing an API key with billing attached; the current browser voice reads as dated.
- **An n8n worked example** inside the sales repo's own automation guide, as one honest example of a repeatable, approval-gated workflow, not a new headline tool.
- **New fictional sibling-tool cases that only change the names in an existing pattern.** The audit found none of these are needed right now; every existing case still earns its place.

## A Few Rules for Using This Page

- Keep facts, estimates and assumptions clearly separate, including on this page: nothing here is a delivery date.
- Add to "Explore Later" freely. Only move something up when it is actually being worked on.
- If a "Later" item stays parked for good, say so plainly and remove it, rather than let this page collect ideas nobody intends to build.
- Repository content and commit activity are not evidence of adoption. Internal use is not independent validation. This page tracks work, not proof.
