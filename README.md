# Hi, I'm Shaun

I work in B2B sales as a Solutions Consultant at AiCore, a UK apprenticeship provider that trains companies' teams to use AI in practical ways. Here I share personal projects that show how AI can make everyday commercial work clearer, faster and easier to check. The examples are fictional or have had real details removed. I share what worked, what didn't, and what I'd change.

## What Would Help You Today?

You don't need to code or install anything to try these. Pick the job you want help with.

| What you need | Start here |
| --- | --- |
| Help with a sales task | [Pick a sales job and copy the prompt](https://github.com/shaunmarsden/practical-ai-sales-workflows/tree/main/recipes) |
| Help getting started with AI at work | [Try one ordinary task with your approved AI tool](https://github.com/shaunmarsden/practical-ai-adoption/blob/main/guides/you-have-been-given-ai-at-work.md) |
| A tool for another everyday job | [Find a tool for meeting notes, lists, decisions and more](https://github.com/shaunmarsden/sibling-projects) |
| Plainer emails, notes, reports or posts | [Paste writing into a private checker, or use a skill](https://github.com/shaunmarsden/say-it-plainly) |
| Sorting job adverts against what you need | [Paste a skill into any AI chat, then your adverts](https://github.com/shaunmarsden/find-my-next-job) |

**[Watch a recorded run &rarr;](https://shaunmarsden.github.io/practical-ai-sales-workflows/)** replays a real skill turning a fictional call transcript into evidence-labelled output. Every line traces back to where it came from. It doesn't make a live AI call.

Rather read than watch? [Follow the same example as a written walkthrough](https://github.com/shaunmarsden/practical-ai-sales-workflows#-see-one-complete-test), from the fictional transcript to the finished output and its scored review.

## Featured Projects

### [Practical AI Sales Workflows](https://github.com/shaunmarsden/practical-ai-sales-workflows)

A library of AI workflows for everyday B2B sales work, from preparing for a call to following up, handling objections and keeping a CRM honest. Each has a [one-page recipe card with a prompt you can copy](https://github.com/shaunmarsden/practical-ai-sales-workflows/tree/main/recipes).

Available doesn't mean independently proven. The [evidence-status matrix](https://github.com/shaunmarsden/practical-ai-sales-workflows/blob/main/EVIDENCE-STATUS.md) separates fictional tests, logged real use and independent tests. No independent use has been logged yet.

There's also a guide to setting up your AI for sales work, whatever tool your company gives you, and a scored comparison of the same task run with no setup in Claude, ChatGPT and Gemini.

### [Practical AI Adoption](https://github.com/shaunmarsden/practical-ai-adoption)

Plain-English guides for people who want to use AI at work but don't have a technical background. They start with writing a better brief and checking what comes back, then build up to useful workflows.

### [Say It Plainly](https://github.com/shaunmarsden/say-it-plainly)

Five skills that make an AI tool review or rewrite your writing in plain words, for emails, meeting notes, reports and posts, plus a [private checker](https://shaunmarsden.github.io/say-it-plainly/) that runs in your browser and sends nothing anywhere. In my own small tests, a one-paragraph instruction kept a draft's claims as well as a skill did. The first version of the notes skill added claims the paragraph did not, and after I tightened it the two matched. A bare request did worst on emails and reports. I'd call the skills a first draft.

### [Commercial Career Pivot Workbench](https://github.com/shaunmarsden/commercial-career-pivot-workbench)

A workflow for sales and commercial people thinking about a career change. It checks the evidence at each step.

### [Find My Next Job](https://github.com/shaunmarsden/find-my-next-job)

A skill for anyone looking for work, not just in sales. Paste it into any AI chat with your experience, your limits on hours, place and pay, and the adverts you've found. It sorts them into worth applying for, check one thing first, and skip, with links and reasons. In my small test with made-up jobseekers, it sorted 33 of 33 adverts correctly. Asked the same thing with no skill, the AI got 29 right, and kept suggesting a job below the pay the person said they needed.

## The Same Method, Applied Beyond Sales

I use the same standard in two more places: a real worked example with a hard case built in on purpose, and a review that checks whether the tool caught it.

### [Sibling Projects](https://github.com/shaunmarsden/sibling-projects)

Nineteen free tools. Most take a pattern from the sales repo and rebuild it for a wider audience: keeping facts and assumptions apart in any meeting write-up, building a scoring rubric for any AI output, checking whether the evidence backs up a tracked status, deciding what to send when someone has gone quiet, and more.

Not sure which one fits? [Try the interactive picker &rarr;](https://shaunmarsden.github.io/sibling-projects/) or, if you'd rather paste a description into an AI chat, [use the router](https://github.com/shaunmarsden/sibling-projects/blob/main/ROUTER.md).

Want to build your own skill from scratch instead? [Book to Skill](https://github.com/shaunmarsden/book-to-skill) turns a book you already own into a Claude skill. Along with the sales workflows above, it's one of the two patterns most of these tools are based on. The newest, [Do These Actually Match?](https://github.com/shaunmarsden/do-these-actually-match), is based instead on the Conflicting evidence label in the sales repo's methodology.

I'm also trying the same idea for commercial teams more widely. These are still early: [AI for Commercial Teams](https://github.com/shaunmarsden/ai-for-commercial-teams), [Sales Conversation Gym](https://github.com/shaunmarsden/sales-conversation-gym), [Sales Proof Bench](https://github.com/shaunmarsden/sales-proof-bench), and [Sales Value Workshop](https://github.com/shaunmarsden/sales-value-workshop).

## What I'm Working On Next

The [roadmap](ROADMAP.md) covers all of this, not just the sales repo. In short: fewer assumptions, easier to pick up, more real testing, and more work on what already exists before I build anything new.

## Also Worth Knowing About

Not mine, but useful: [Wispr Flow Media Pause](https://github.com/kierzio/wispr-flow-media-pause) pauses whatever you're playing while you dictate with Wispr Flow, instead of muting it. It's built for USB audio interfaces that macOS can't mute by itself. A small thing, but it annoys you every time until someone fixes it.

Also worth having if you dictate on macOS: [macos-mic-keepwarm](https://github.com/drewburchfield/macos-mic-keepwarm) keeps the microphone awake. That fixes the 2-5 second delay before push-to-talk starts, so Wispr Flow, SuperWhisper and similar apps start listening at once, instead of losing the first half-second of what you say.

Found on LinkedIn: [Premortem](https://gist.github.com/oscheers/9d722938ce35dab2a07832e69b688871), a Claude skill by Ollie Scheers. It assumes a project has already failed and works back to why. Then it sorts the causes into tigers (real risks that need an owner and a plan to reduce them), paper tigers (risks that sound scary but don't deserve much attention) and elephants (things people already suspect but nobody says out loud). It ends with actions that each have an owner, and tripwires, not a longer list of worries.

## A Few Rules I Try to Follow

- Start with a real problem, not a tool looking for a use case
- Keep facts, estimates and assumptions clearly separate
- Keep a person responsible for the final decision
- Don't put sensitive information into tools that aren't approved
- Publish the honest score, not just the polished result

I'm learning as I go and sharing the useful bits here.
