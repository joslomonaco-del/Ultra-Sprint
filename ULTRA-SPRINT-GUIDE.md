# The Ultra Sprint

### A condensed, AI-assisted design sprint method for rapid ideation, prototyping, and testing.

**Version 0.3** · Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

## Table of Contents

1. [What Is the Ultra Sprint?](#what-is-the-ultra-sprint)
2. [Principles](#principles)
3. [Before You Start](#before-you-start)
4. [Sprint Day - Overview](#sprint-day--overview)
5. [Part 1 - Frame the Problem (1 hour)](#part-1--frame-the-problem-1-hour)
6. [Part 2 - Research & Sketch (1.5 hours)](#part-2--research--sketch-15-hours)
7. [Part 3 - Present & Decide (30 minutes)](#part-3--present--decide-30-minutes)
8. [Part 4 - Prototype (2.5 hours)](#part-4--prototype-25-hours)
9. [Test Day](#test-day)
10. [Rules & Governance](#rules--governance)
11. [Materials Checklist](#materials-checklist)
12. [Facilitator Tips](#facilitator-tips)
13. [Adapting & Contributing](#adapting--contributing)
14. [Glossary](#glossary)
15. [Changelog](#changelog)

---

## What Is the Ultra Sprint?

The Ultra Sprint is a compressed design sprint that fits problem-framing, ideation, sketching, prototyping, and user testing into roughly **one full sprint day (~6 hours)** plus a separate **test day (~2.5 hours)**. It borrows its backbone from Google's five-day Design Sprint but dramatically shortens the timeline by leaning on AI tools for research, challenge generation, and prototyping.

It is designed for small teams (2–5 participants plus a dedicated facilitator) who want to go from a raw idea to a testable prototype fast - without sacrificing the structured thinking that makes design sprints valuable.

**Who is this for?** Innovation teams, startup teams, freelancers, hackathon participants, student projects - anyone who needs to validate an idea quickly with real users.

**What makes it different from a classic Design Sprint?**

The classic Google Ventures Design Sprint spans five days with dedicated phases for mapping, sketching, deciding, prototyping, and testing. The Ultra Sprint compresses all of this into roughly one day of work plus a separate test session, by making three key trade-offs: it replaces lengthy group discussions with fast, time-boxed lightning phases; it offloads research and challenge discovery partly to AI; and it uses AI-assisted prototyping tools to build testable artifacts in hours rather than a full day. The result is a method that's far less costly in time and coordination, at the expense of some depth - which is an intentional choice for early-stage ideas where speed of learning matters more than polish.

---

## Principles

These principles guide every decision in the Ultra Sprint. When in doubt, come back to them.

**1. Speed over perfection.** Several phases are marked with a ⚡ (lightning phases). When you see that symbol, it means the goal is momentum, not polish. Getting something down quickly is always better than agonising over the right answer. Perfect is the enemy of tested.

**2. Humans decide, AI assists.** AI is used to generate options, surface blind spots, and build prototypes. It never votes, never decides, and never replaces the judgment of the people in the room. Every decision point belongs to the participants.

**3. Structured democracy.** Votes are democratic by default. Every participant's voice carries equal weight. The one exception: a designated Decider (see Rules & Governance) can override the group, but only after hearing everyone's position.

**4. Show, don't tell.** Sketching and prototyping are the primary communication tools. Words describe; drawings and prototypes reveal. The method pushes toward visual output as fast as possible.

**5. Test with real people.** The prototype exists for one reason: to be put in front of real potential users. Every decision during the sprint day should be made with that test session in mind.

---

## Before You Start

### Assemble Your Team

You need between **2 and 5 participants**. The sweet spot is 4. The participant count does not include the facilitator, who is a dedicated role (see below).

Ideally, your team includes a mix of perspectives: someone close to the problem, someone with design instincts, someone technical enough to wrangle a prototype, and someone who can think like the end user.

### The Facilitator

The Ultra Sprint requires a dedicated **facilitator** - a person whose sole job during the sprint is to run it. The facilitator keeps time, reads instructions aloud, manages transitions between phases, and makes sure lightning phases don't spiral into debates. The facilitator **does not participate**: they don't write post-its, don't sketch, don't vote, and don't prototype. Their full attention is on keeping the group moving and the process on track.

The facilitator is not counted in the participant count. A sprint with "4 participants" has 5 people in the room: 4 participants and 1 facilitator.

### Prepare Your AI Tools

The Ultra Sprint uses AI at specific, clearly marked moments. The AI tooling landscape is evolving rapidly, so rather than prescribing specific products, the method only specifies *where* AI is used and *what kind* of AI is needed. Use whatever is the most capable and efficient option available to you at the time. The four categories you'll need are:

- A **conversational LLM** for generating challenges and obstacles (Parts 1.1 and 1.3).
- An **AI-powered search tool** for finding real-world inspiration (Part 2.1).
- An **AI prototyping tool** capable of generating functional front-end interfaces from descriptions or images (Part 4).
- Optionally, a **transcription/summarisation tool** for capturing tester feedback on Test Day.

Before the sprint, the facilitator should verify that at least the participants who need them have working access to tools in each category.

### Prepare Your Space

You'll need a room (physical or virtual) with wall space or a whiteboard for hanging post-its. Prepare enough materials for everyone (see the Materials Checklist at the end of this guide).

### Set the Topic

Before sprint day, the facilitator should prepare a short, clear statement of the problem or opportunity the sprint will tackle. This can be as simple as one sentence: *"We want to explore how [target users] could [do something better/differently]."* Share it with participants the day before so they arrive with some context.

---

## Sprint Day - Overview

Here's the full day at a glance. Total time: approximately **6 hours** (not counting breaks and lunch).

| Block | Duration | Summary |
|---|---|---|
| **Part 1** - Frame the Problem | 1 hour | Define challenges, a dream goal, and dream killers |
| **Part 2** - Research & Sketch | 1.5 hours | Research inspiration, then sketch individual solutions |
| **Part 3** - Present & Decide | 30 min | Present sketches, critique, vote on the concept to prototype |
| **Part 4** - Prototype | 2.5 hours | Build a realistic-looking prototype using AI tools |

Plan for short breaks between parts and a proper lunch break. A 10-minute break between Part 1 and Part 2 works well, followed by a **lunch break after Part 2** (before presentations begin). After lunch, another short break between Part 3 and Part 4 keeps energy up for the prototyping push.

---

## Part 1 - Frame the Problem (1 hour)

The goal of Part 1 is to align the team on what matters: the challenges, the ambition, and the biggest risks. Everything produced here stays visible on a wall or board for the rest of the sprint.

---

### ⚡ Step 1.1 - General Challenges (25 minutes)

**Type:** Lightning phase · **AI:** Yes (LLM)

**What you're doing:** Building a shared list of the biggest challenges related to your problem space.

**How to run it:**

1. **Silent brainstorm (5 min).** Every participant grabs post-its and a marker. Set a timer for 5 minutes. Each person writes down as many potential challenges as they can think of - one challenge per post-it. No discussion, no filtering. Quantity over quality.

2. **AI challenge generation (5 min).** The facilitator opens an LLM and prompts it with something like:

   > *"We are working on [brief description of the idea/problem]. We've listed some challenges ourselves. Now, give us 10 potential challenges we might not have thought of. Be specific and non-obvious."*

   Read the AI's 10 suggestions out loud to the group, one by one.

3. **Quick hand vote on AI suggestions (5 min).** For each of the AI's 10 challenges, do a fast hand vote: *"Is this important enough to keep?"* If a majority raises their hand, one participant writes it on a new post-it and adds it to the collection. If not, move on immediately. Don't debate - this is a lightning phase.

4. **Dot vote to select ~5 challenges (10 min).** Stick all the post-its (human-written and AI-contributed) on a wall. Give each participant a small number of sticky dots (3 dots per person works well for groups of 3–5). Everyone places their dots on the challenges they consider most critical. The ~5 challenges with the most dots are your **selected challenges**. Keep them visible.

---

### Step 1.2 - Dream Goal (10 minutes)

**Type:** Standard phase · **AI:** No

**What you're doing:** Defining the single most ambitious, optimistic outcome the team could achieve in two years thanks to this idea.

**How to run it:**

1. **Silent write (5 min).** Each participant writes one post-it describing the best possible place the team/product could be in two years. Think very optimistically - this is meant to be aspirational, not realistic. Examples: *"We're the default tool for X in Europe"* or *"50,000 people use this weekly and it changed how they Y."*

2. **Share and vote (5 min).** Each person reads their dream goal aloud (30 seconds each, no pitching). Then do a quick hand vote: *"Which dream goal should we focus the sprint around?"* The winning post-it becomes **the Dream Goal**. Hang it somewhere prominent - it stays visible for the entire sprint.

**Why no AI here:** The dream goal should come from the genuine ambition and vision of the people in the room. AI tends to produce generic, hedged goals. This one needs to feel personal.

---

### ⚡ Step 1.3 - Dream Killers (20 minutes)

**Type:** Lightning phase · **AI:** Yes (LLM)

**What you're doing:** Identifying the biggest obstacles that could prevent you from reaching the Dream Goal.

**How to run it:**

1. **Silent brainstorm (5 min).** Each participant writes about 3 post-its describing what could stop the team from reaching the Dream Goal. Be specific: not *"competition"* but *"a big player launches a free version of this before we gain traction."*

2. **AI obstacle generation (5 min).** The facilitator prompts the LLM:

   > *"Our dream goal is: [paste the Dream Goal]. What are the most likely obstacles that could prevent us from getting there? List 5–8 specific, realistic obstacles."*

3. **Read and compare (5 min).** The facilitator reads aloud all the participant post-its first, then the AI's suggestions. Group similar ideas together informally.

4. **Dot vote for the top 3 (5 min).** Give everyone 2 sticky dots. Vote on the combined set. The **3 Dream Killers** with the most dots are selected. Hang them next to the Dream Goal.

At this point, you should have a visible display on your wall: the Dream Goal, the 3 Dream Killers, and the ~5 selected challenges.

---

## Part 2 - Research & Sketch (1.5 hours)

The goal of Part 2 is to go from a shared understanding of the problem to individual, concrete solution sketches. It starts with external inspiration and ends with detailed visual blueprints.

---

### Step 2.1 - Inspiration Research (30 minutes)

**Type:** Standard phase · **AI:** Yes (AI-powered search)

**What you're doing:** Finding real-world examples of companies or products that have already solved a similar problem - or part of it.

**How to run it:**

1. **Search (20 min).** Each participant (or pairs, if the team is large) uses an AI-powered search tool to find companies, products, or projects that relate to your problem space. You're not looking for direct competitors only - look for *analogous solutions* in other industries too. For example, if your problem is about simplifying a complex onboarding flow, look at how completely different products (a bank, a game, a government service) solved their onboarding.

   For each interesting find, write a post-it with the company/product name and a very brief summary of the relevant idea (1–2 sentences max).

2. **Present (10 min).** Each participant quickly presents their finds (1–2 minutes each). Stick the post-its on the wall. No voting needed - these are raw inspiration, not decisions.

**Tip:** Aim for 3–5 examples per participant. Breadth matters more than depth here.

---

### Step 2.2 - Sketching (1 hour)

**Type:** Standard phase · **AI:** No

This is the heart of the sprint. Each participant works individually to develop a solution concept, moving from loose notes to a detailed visual blueprint. The phase has three sub-steps with increasing fidelity.

#### 2.2a - Ideas & Notes (20 minutes)

Grab paper and a pen. This is unstructured thinking time. Review everything on the walls - the challenges, the dream goal, the dream killers, the inspiration research. Then start writing, doodling, and exploring. Follow your instincts. Jot down features, user flows, key screens, taglines, mechanisms, business model ideas - anything that comes to mind.

There's no format requirement. This is your scratch pad. The only rule: by the end of 20 minutes, you should have a favourite idea or direction that you want to develop further.

#### ⚡ 2.2b - Speed Sketches (8 minutes)

**Type:** Lightning phase

Take a sheet of paper and divide it into 4–8 boxes (fold it, or draw a grid). Set a timer for 8 minutes. Now quickly re-sketch your favourite idea into 4–8 different visual variations - one per box. Each box might show a different screen, a different layout, a different angle on the same concept, or a completely different take.

The point is to force divergence. Don't refine a single idea; explore multiple versions of it. Ugly is fine. Speed is everything.

#### 2.2c - 3-Part Blueprint (30 minutes)

Now you'll commit to one direction and flesh it out.

1. **Choose one box** from your speed sketches - the one that excites you most.

2. **Prepare your canvas.** Take three sheets of A4 (or Letter) paper, orient them horizontally (landscape), and tape or stick them together vertically so you have a tall, three-panel canvas.

3. **Draw your blueprint.** Use the full 30 minutes to redraw your chosen concept across the three panels, representing the **three most essential parts** of the idea. These might be three key screens of an app, three stages of a user journey, or three views of a physical product - whatever makes sense for your concept.

**Important rules for the blueprint:**

- Use **meaningful text**, not placeholder text. If a heading says something, write the real words. If a button has a label, write the actual label. This forces you to think concretely about the experience.
- Add **annotations** on post-its and stick them onto the blueprint wherever something needs explanation.
- It should be understandable by someone who wasn't inside your head during the ideas phase.

This blueprint is what you'll present to the group in Part 3.

---

## Part 3 - Present & Decide (30 minutes)

The goal of Part 3 is to share all the concepts, improve them with group input, and select the one that will be prototyped.

---

### Step 3a - Gallery & Presentations (~15 minutes)

1. **Hang all blueprints** on a wall, side by side, like an art gallery.

2. **Present (3 min per person).** Each participant walks the group through their blueprint. Explain the core idea, the user flow, and why it addresses the challenges and dream goal. Stick to 3 minutes - the facilitator should enforce this.

3. **Silent critique.** After each presentation, there is no group discussion. Instead, participants write improvement ideas on post-its and stick them next to the relevant blueprint.

---

### Step 3b - Improve & Vote (~15 minutes)

1. **Dot vote on improvements.** Once all presentations are done, everyone gets sticky dots (1 dot per improvement post-it). Read through the improvement suggestions on all blueprints and place a dot on any you think are genuinely valuable. An improvement post-it that receives dots from **more than half the participants** is considered adopted - if that blueprint is chosen, the improvement must be included in the prototype.

2. **Final concept vote.** This is the big decision. All participants vote simultaneously (everyone points at their chosen blueprint on the count of three, or uses a sticky dot on the blueprint itself). The concept with the most votes becomes **the prototype concept**.

   The non-chosen concepts are not discarded. Keep them as backups: if user testing reveals serious problems with the chosen concept, the team can pivot to one of the alternates.

---

## Part 4 - Prototype (2.5 hours)

The goal of Part 4 is to turn the chosen blueprint into a realistic-looking prototype that can be tested with real users.

---

### Step 4.1 - Parallel Prototyping Sprint (30 minutes)

**AI:** Yes (prototyping tool of choice)

Every participant takes a photo of the chosen blueprint (including any adopted improvement post-its) and feeds it into an AI prototyping tool - whichever is the most capable option available at the time of the sprint.

Each participant works independently, prompting the AI and iterating on the output. The goal is to get as close to the blueprint as possible while making it look and feel like a real product.

> **Note:** This phase is designed for digital prototypes (apps, websites, dashboards, etc.). If your concept is a physical product, a service, or something non-digital, you'll need to adapt: consider building a landing page, a clickable slide deck, a video walkthrough, or a physical mock-up using whatever tools and materials are available. The principle is the same - create something realistic enough that a tester can experience the core idea.

---

### Step 4.2 - Select the Best Prototype (15 minutes)

After the first 30 minutes, everyone pauses and takes turns (3 minutes each) showing their prototype to the group. Then, a quick hand vote selects the prototype that best captures the concept.

---

### Step 4.3 - Collaborative Refinement (1 hour 45 minutes)

The rest of the time is spent working together on the chosen prototype. This means:

- One person drives (uses their screen and makes edits in the AI tool) while others give direction and feedback.
- Alternatively, split up specific screens or sections among participants and merge later.
- Focus on making it look **real enough to test**: real copy, plausible data, consistent styling, and functional navigation between the key screens.

Don't chase perfection. The prototype needs to be good enough for a tester to understand the concept and react to it - not good enough to ship.

**Checkpoint questions before wrapping up:**

- Can a tester navigate the core flow without help?
- Does the text feel real, or are there obvious placeholders?
- Are the 3 essential parts from the blueprint all represented?
- Were the adopted improvements from Part 3 included?

---

## Test Day

Test Day happens separately from Sprint Day - ideally within a few days, while the work is fresh.

---

### Setup

- Recruit **5 testers** who could realistically be potential users of the product. They should not have been involved in the sprint.
- Prepare the prototype on a device the tester can interact with naturally (a phone, tablet, or laptop depending on the product).
- Set up a transcription/note-taking tool (or simply a dedicated note-taker) to capture what testers say.
- Prepare a quiet, distraction-free space.

---

### Test Session Structure (25 minutes per tester)

Each tester goes through the same process individually. **Do not test in groups** - you want each person's unfiltered reaction.

**1. Introduction (2 min).** Welcome the tester. Explain that you're testing a prototype, not them - there are no wrong answers. Ask them to think aloud: say whatever comes to mind as they interact with the prototype.

**2. Free exploration (12–15 min).** Hand them the prototype and let them use it. Don't guide them. If they get stuck, note where and why, but resist the urge to explain. Encourage them to keep talking: *"What are you thinking right now?"* or *"What did you expect to happen there?"*

**3. Follow-up questions (8–10 min).** After they've explored, ask questions focused on **how they feel**, not how they'd redesign it. Good examples:

- *"Would you use this on a daily basis? Why or why not?"*
- *"Did any part feel a bit underwhelming or confusing?"*
- *"What was your first impression?"*
- *"Was there a moment where you felt pleasantly surprised - or frustrated?"*
- *"If this existed today, would you recommend it to someone? Who?"*

**What NOT to ask:** Avoid questions that turn the tester into a designer, such as *"How would you change this?"* or *"What features would you add?"* Those answers are almost always misleading. Focus on emotional and behavioural reactions.

**4. Thank and wrap up (1 min).** Thank them, and offer any compensation you promised.

---

### After All 5 Tests

- Review the transcription summaries.
- Look for **patterns**, not outliers. If 3 out of 5 testers struggled with the same screen, that's a signal. If 1 person disliked the colour scheme, that's noise.
- Document the key findings as a simple list of observations (what worked, what didn't, what surprised you).
- If the concept was broadly well-received: iterate and build. If it was heavily disliked on a fundamental level: revisit the backup concepts from Part 3 and consider running another prototype + test cycle.

---

## Rules & Governance

### Voting

All votes are **democratic** by default: every participant's vote carries equal weight, and the majority wins.

**The Decider exception:** If the team designates someone as the Decider (typically a founder, product lead, or project owner), that person has the final say on all decisions. In this case, votes become **alignment votes** - the group still votes, but the purpose is to share opinions and signal preferences to the Decider, who then makes the call. This should be decided and announced before the sprint begins, not mid-session.

### Minimum Team

The method requires at least 2 participants (plus a facilitator). With only 2 participants, voting phases still apply but are naturally simpler - a tie means the two participants must briefly discuss and agree, or defer to a Decider if one is designated.

### AI's Role

AI generates options for the group to evaluate. AI never votes, never makes final decisions, and never overrides a participant's judgment. When an AI-generated challenge, obstacle, or idea is adopted, it's because the humans voted it in - not because the AI suggested it.

### Lightning Phases (⚡)

Steps marked with a ⚡ are lightning phases. The facilitator should explicitly announce at the start of each one: *"This is a lightning phase - it's not important to get it perfect, it's important to get it fast."* This framing gives the group permission to move quickly and avoid rabbit holes.

---

## Materials Checklist

Prepare these before Sprint Day:

- Post-it notes (at least 2 packs per participant; ideally a single colour for consistency, or multiple colours if you want to colour-code by phase)
- Markers or thick pens (one per participant - thin pens are hard to read on post-its from a distance)
- Sticky dots for voting (small round stickers; 10–15 per participant should cover all votes)
- A4/Letter paper (at least 10 sheets per participant for sketching)
- Tape or adhesive putty (for hanging blueprints and post-its on walls)
- A timer (phone timer is fine; a large visible timer is better)
- A laptop or device per participant with access to the chosen AI tools
- Wall space or a large whiteboard
- Camera or phone
- A printed or shared copy of this guide for the facilitator

For Test Day, add: the device with the prototype loaded, a transcription tool set up and tested, and a quiet room.

---

## Facilitator Tips

**Before the sprint:** Read this entire guide. Prepare the topic statement. Set up the room. Test your AI tools.

**During the sprint:**

- Be strict about time. Lightning phases especially tend to balloon if you let them. Use a visible countdown timer and give a 1-minute warning before each deadline.
- Read the instructions for each step aloud at the start of that step. Don't assume everyone read the guide.
- During silent brainstorming phases, enforce silence. Even helpful comments derail individual thinking.
- During voting, make sure votes happen simultaneously (everyone reveals at the same time) to avoid anchoring bias.
- If a discussion is going in circles, call it: *"Remember that it's ok if it isn't perfect. Let's vote and move on."*
- Take photos of the wall at the end of each part. Post-its fall off; walls get erased. A photo record is cheap insurance.

**After the sprint:** Compile a brief sprint summary with photos of the wall, the chosen concept, the prototype link, and the test day plan. Share it with the team within 24 hours.

---

## Adapting & Contributing

The Ultra Sprint is a living method, released under **Creative Commons Attribution 4.0 (CC BY 4.0)**. You are free to share, adapt, remix, and build upon it for any purpose, including commercial use, as long as you give appropriate credit.

### How to Adapt It

This method is intentionally opinionated but modular. Here are some examples of dimensions you could adjust:

**Timing.** The durations given are starting points. If your team consistently finishes the Ideas & Notes phase in 15 minutes, shorten it. If your prototype needs more polish, extend Part 4. Track what works and adjust for your next sprint.

**AI tools.** The AI landscape changes fast. What matters is having a capable tool for each of the four categories (conversational LLM, AI search, AI prototyping, transcription). Re-evaluate your tool choices before each sprint rather than defaulting to habit.

**Team size.** The method is designed for 2–5 participants, but consider adapting the method for differently-sized teams.

**Non-digital products.** Part 4 assumes a digital prototype. For physical products, services, or experiences, replace the AI prototyping step with whatever medium makes the concept tangible: a physical mock-up, a role-played service interaction, a video prototype, or a detailed storyboard.

**Remote teams.** The method was designed to be in-person but could work remotely with different tools, and by modifying the method to make it run smoothly.

### How to Contribute

- **Issues:** Use issues to propose changes, report problems, or share how a sprint went with your suggested tweaks.
- **Pull requests:** Submit a PR if you've tested a modification and want to propose it for the main guide. Include a brief description of the change, why you made it, and how it went when you tested it.
- **Forks:** Fork freely. If you build a significantly different variant, consider linking back to the original.

When contributing, follow this convention for the changelog: describe *what* changed and *why*, not just *that* it changed.

---

## Glossary

**Lightning phase (⚡):** A time-boxed step where speed is explicitly prioritised over quality. The facilitator announces this framing at the start.

**Dream Goal:** The single most optimistic, aspirational outcome the team could reach in two years. Chosen by vote in Part 1 and displayed prominently throughout the sprint.

**Dream Killers:** The top 3 obstacles most likely to prevent the team from reaching the Dream Goal. Chosen by dot vote in Part 1.

**3-Part Blueprint:** A detailed, three-panel sketch of a solution concept, created by each participant in Part 2. It represents the three most essential parts of the idea with real text and annotations.

**Speed Sketches:** A rapid-fire exercise (8 minutes) where a participant draws 4–8 variations of their idea in small boxes on a single sheet.

**Dot vote:** A voting method where each participant gets a fixed number of sticky dots and places them on the items they consider most important. Items with the most dots win.

**Alignment vote:** A vote used when a Decider is designated. The group still votes to share opinions, but the Decider makes the final call.

**Decider:** An optional designated person (founder, project lead, etc.) who has final authority over all decisions. Must be announced before the sprint begins.

---

## Changelog
