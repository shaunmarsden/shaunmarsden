# Roadmap

One roadmap for everything here, rather than one per repo. It covers [Practical AI Sales Workflows](https://github.com/shaunmarsden/practical-ai-sales-workflows), the [Sibling Projects](https://github.com/shaunmarsden/sibling-projects) family of nineteen tools built from its patterns, and the commercial-teams family ([AI for Commercial Teams](https://github.com/shaunmarsden/ai-for-commercial-teams), [Sales Conversation Gym](https://github.com/shaunmarsden/sales-conversation-gym), [Sales Proof Bench](https://github.com/shaunmarsden/sales-proof-bench), [Sales Value Workshop](https://github.com/shaunmarsden/sales-value-workshop)).

It also covers two newer repos that sit outside those three families. [Practical AI Adoption](https://github.com/shaunmarsden/practical-ai-adoption) is general guides to using AI for anyone at work, not just sales. [Commercial Career Pivot Workbench](https://github.com/shaunmarsden/commercial-career-pivot-workbench) is a workflow for sales and commercial people thinking about a career change, which checks the evidence at each step.

Each repo keeps its own detailed roadmap where it has one. This page is the short version, grouped by the kind of work each item is: making something already built easier to take up, testing something nobody independent has logged using yet, finishing limited work that's already justified, maintaining something that's fine as it is, or exploring something new later.

On 3 August 2026 I checked the whole portfolio. It had 25 public source repositories, none archived, all with `main` as the default branch, and I updated this page to match what's in each one. On 4 August 2026 a follow-up pass asked whether a busy salesperson with no technical background can find, understand and try what's here. Its findings are below.

I added two more repositories after that, Practical AI Adoption and Commercial Career Pivot Workbench. They weren't part of that count or the three-family description. The portfolio now has 27 public source repositories. Nothing on this page is a delivery date.

## Make Existing Work Easier To Adopt

Nothing outstanding right now. Two rounds of fixes are done.

The readability and adoption pass on 4 August 2026 found six fixes: SKILL.md copy-paste instructions, the picker's visibility, the ROUTER.md regression, the commercial-teams cross-link, two notes telling similar sibling tools apart, and the missing template file.

A follow-up check across all eighteen sibling tools fixed three more pairs with confusing names: Skill Author and Book to Skill, Make the Case and Brief Your Advocate, and What's Actually Causing This Delay and Post-Mortem Builder. It also fixed a gap in the Sibling Projects picker. The picker only ever covered six of the eighteen tools without saying so, and gave a visitor no way back to the rest if their situation wasn't one of those six.

## Test Existing Work

- **No repository in the portfolio has a logged use by anyone but me yet.** The feedback form and Discussions link on the sales repo show no logged activity. The same is true across all nineteen sibling tools and the whole commercial-teams family. That gap matters more right now than anything a new feature would close.
- **Only one Practical AI Sales Workflows job still has no recorded real use.** It's reviewing an outbound campaign. Fourteen jobs have a logged real-use test. One of those found a limit: it correctly stopped a stalled-decision case, rather than proving the method can move a buyer who really can't decide. Prepare for a Sales Call has been used live but not formally logged. That's a middle category of its own, not a second job with no real use.
- **Before Sales Proof Bench adds its next comparison type**, it should credit and build on the cross-model comparison Practical AI Sales Workflows already ran and scored, rather than repeat the same kind of case as if it were new.
- **Practical AI Sales Workflows' approval-gated sales-copilot method still has no independent test.** [The guide, template, fictional test and evaluation](https://github.com/shaunmarsden/practical-ai-sales-workflows/blob/main/guides/build-an-approval-gated-sales-copilot.md) are public. There's also a live finding from my own use, with real details removed. I use a private version internally, but nobody independent has checked that private setup. The next useful evidence is an attempt by someone outside the project, not another finding of mine or more command modes.

## Finish Bounded Work Already Justified

Nothing outstanding right now. Both items here are done.

Sales Conversation Gym's AI-plays-the-buyer mode is now a built prompt (`guides/ai-plays-the-buyer.md`). It's the one new mechanic the commercial-teams family adds beyond the sales repo.

Sales Value Workshop's enterprise case tests a harder, different "not yet" outcome. The block is a security and procurement gate, rather than the missing owner in the existing case.

## Maintain

- Practical AI Sales Workflows' methodology, evidence matrix and governance docs are in good shape. They don't need more scope, only the real-work tests above.
- The Sibling Projects router is accurate. All eighteen linked tools exist and match their descriptions, and this audit found no broken links.
- Most of the nineteen sibling tools are complete and consistent as built. They need the fixes above that tell similar tools apart, and real use, not more building. The newest, Do These Actually Match?, hasn't had its own maintenance check yet.
- `book-to-skill` is complete as built. Treat it as maintenance, not something to expand.

## Explore Later, Deliberately Not Yet

These aren't forgotten. They're on hold, and most are waiting on something specific rather than just priority.

- **Sibling repos for finance, HR or operations.** The plan was always to find a real practitioner from that function to lead it with me. I didn't want to build it alone by analogy. The sales repo works because I test it against real deals. I haven't found a practitioner, so I'm not pursuing this until I do.
- **BVA and workshop-style enterprise content.** This reads like AiCore's own method rather than general advice that suits small businesses. It may need to stay private, or be properly generalised, before it's worth publishing.
- **A portfolio map diagram, considered and set aside for now.** The readability pass asked whether the profile README needs one showing how the three families relate. It concluded that a visitor's real question is "which of these fits my problem", and a plain linked list of jobs answers that better than a family-tree image would. The evidence-status matrix link answers separately whether something has been tested, rather than folding that into the list. Only come back to the diagram if a later check finds people still can't find their way with the cross-links above.
- **A proper visuals and short-video pass** for the sales repo, beyond the diagrams already there. I've flagged before that this needs a proper focused session, not a few minutes here and there.
- **Better, more natural voices for the interactive demo.** This is blocked until I either generate the audio files directly or share an API key with billing attached. The current browser voice sounds dated.
- **An n8n worked example** in the sales repo's own automation guide: one example of a repeatable, approval-gated workflow, not a new headline tool.
- **New fictional sibling-tool cases that only change the names in an existing pattern.** The audit found none are needed right now. Every existing case is still worth keeping.

## A Few Rules for Using This Page

- Keep facts, estimates and assumptions clearly separate, including on this page: nothing here is a delivery date.
- Add to "Explore Later" freely. Only move something up when I'm working on it.
- If a "Later" item stays parked for good, say so and remove it, rather than let this page collect ideas nobody intends to build.
- Repository content and commit activity don't show that anyone has taken something up. Internal use isn't independent proof. This page tracks work, not proof.
