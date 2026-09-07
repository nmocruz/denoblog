---
title: 'The Forger’s Spell: When a Room Can’t Tell a Masterpiece from a Fake'
date: '2025-09-01T16:00:00.000Z'
author: Nuno Cruz
tags:
  - Software Engineering
  - Architecture
  - Leadership
draft: false
---

There is a version of the Peter Principle that is less about ego or status than about judgment: a room can evaluate only what it has the depth to evaluate.

Once a decision demands more technical depth than the room possesses, errors begin to run in both directions. Weak ideas pass because they look convincing. Strong ideas fail because they look unfamiliar. And when nobody is clearly accountable for the result, neither kind of error has to be corrected.

The room becomes unable to tell a masterpiece from a fake.

### The Peter Principle Is a Structural Problem

The Peter Principle describes a familiar tendency in hierarchies: people are promoted for succeeding in one role until they reach a role that demands a different kind of competence—one they were never evaluated for.

That is not an insult. Someone can be excellent at delivery, people management, commercial judgment, or keeping a team calm under pressure and still find themselves responsible for a decision that requires deep technical verification. The skills that brought them into the room may not be the skills needed to judge the matter before it.

The danger is that this gap rarely announces itself. Often, nobody in the room knows it is there.

### The Forger Who Fooled the Experts

One of the clearest illustrations comes from art.

In the 1930s and 1940s, the Dutch painter Han van Meegeren produced paintings in the style of Johannes Vermeer, whose small body of known work made any discovery immensely valuable. Van Meegeren did not merely copy existing paintings. He created the works experts hoped to find, tailored to their theories about a missing period in Vermeer’s career.

One of the leading Vermeer authorities declared his most famous forgery a masterpiece. More sales followed. During the war, one painting reached Hermann Göring. After the war, that sale exposed Van Meegeren to an accusation of collaborating with the enemy. To defend himself, he confessed to the lesser crime of forgery and demonstrated his method by painting another work under supervision.

The experts he fooled were not amateurs. They had reputation, seniority, and highly trained eyes. What they lacked was a reliable way to test the claim independently. Their judgment depended heavily on connoisseurship: matching style against expectation. Van Meegeren succeeded because he painted for the expectation.

### One Blind Spot, Two Opposite Errors

The same weakness that authenticates a fake can also reject the real thing.

If judgment rests on whether something resembles an expected pattern, then a genuine but unconventional work is vulnerable. A polished imitation feels right; an original that breaks convention feels wrong. Neither response establishes what the work actually is.

Technical organizations make the same mistake. A shallow solution can pass because it uses familiar diagrams, fashionable vocabulary, and reassuring abstractions. A sound solution can be rejected because it crosses an organizational boundary, questions an established pattern, or arrives as working code rather than a polished presentation.

A lack of technical depth does not make a room consistently gullible or consistently skeptical. It makes the room unreliable. Its decisions follow familiarity rather than truth.

### When Technical Language Replaces Technical Judgment

From inside the room, both errors look reasonable. They arrive as confident arguments full of the right vocabulary.

An objection to a sound proposal may be discomfort with an unfamiliar approach translated into technical language after the fact. Approval of a weak proposal may rely on the same vocabulary because the proposal has the expected shape of a good answer. In both cases, presentation fills the space where verification should have been.

Technical language is not technical evidence. In a room with enough depth, a hollow argument can be tested against the substance: state boundaries, failure modes, memory use, network behavior, operational cost. In a room without that depth, confidence becomes a proxy for correctness.

That is the forger’s advantage. The surface is easier to manufacture than the substance.

### When Meetings Become a Substitute for Design

The art analogy has a limit. Van Meegeren knew he was committing fraud. In software organizations, deliberate deception is far less common. A more ordinary problem is sincere overconfidence.

The ability to produce good work and the ability to recognize it are closely related. When a person lacks the depth to design a sound system, they may also lack the means to see why their design is weak. The blind spot has no built-in alarm.

This helps explain how activity can replace progress. Meetings, alignment workshops, governance forums, and strategy decks are useful when they coordinate real work. But an organization can begin to treat the act of discussing a problem as its response to the problem. A meeting is held, concerns are acknowledged, actions are vaguely agreed, and leadership can report that the issue is being addressed—even when nothing in the system changes.

The meeting provides the appearance of movement without the risk of a measurable result. It also shelters ideas from contact with reality. In a presentation, an architecture can be infinitely scalable, elegantly decoupled, and almost free. A compiler, a load test, or a production environment is less accommodating.

Bad decisions can survive in this environment because the same room that made them is also allowed to decide whether they worked. Without technical verification, another meeting can reinterpret failure as partial progress, a need for further alignment, or the beginning of a new strategic phase.

Past failures are then explained away: the team lacked maturity, execution fell short, or priorities changed. Sometimes those explanations are true. But when every failure is attributed to execution and never to the design or the decision-makers, the organization loses the feedback that might improve its judgment.

The result need not involve dishonesty. Someone who believes completely in a weak idea may present it more convincingly than someone who understands a difficult idea well enough to acknowledge its trade-offs. To a room unable to inspect the system, certainty can look like competence.

### When the Enabler Becomes the Blocker

This pattern becomes especially costly when technical authority rests with someone who lacks technical depth. A leader may have little or no experience building software or reasoning about architecture, yet still hold final authority over both. The role gives them the power to decide, but not the knowledge to test whether the decision is sound.

That gap creates a powerful incentive. If expertise cannot establish their position, control can. They place themselves at the centre of every decision, require proposals to pass through them, and make their approval the visible source of progress. Decision-making becomes a way to demonstrate rank.

A challenge then carries more weight than an ordinary technical disagreement. Accepting the better argument may feel like admitting that the authority belonged to someone else. The original decision must therefore stand—even when the evidence shows it is wrong—because reversing it would weaken the image of the leader as the person in charge. Something must be decided, announced, or blocked so that everyone can see who holds the power.

This does not require a calculated plan. The behaviour may come from insecurity, self-preservation, or a sincere belief that leadership means always having the final answer. But the organizational effect is the same: authority stops serving the decision, and the decision starts serving authority.

Real enablement absorbs complexity for others. It produces resilient libraries, automated test and deployment pipelines, clear domain boundaries, useful standards, and reference implementations that have survived contact with a real system. That work requires hands-on engineering depth.

Without that depth, enablement can collapse into control: review boards, documents, recurring meetings, and layers of approval. These tools may serve a purpose, but they are poor substitutes for working infrastructure and testable guidance. The organization builds tollbooths where it needed bridges.

Engineers who can demonstrate a solution then create an uncomfortable comparison. A prototype built in two weeks may answer a question that a committee has discussed for six months. If reviewers cannot challenge it on technical grounds, the debate often moves to process: it lacks enterprise alignment, it has not passed the right board, or it is too concerned with implementation detail.

The central question—does it work?—goes unanswered. Answering it is no longer the real purpose of the process. Preserving who gets to decide is.

The person appointed to enable the engineers has now become their main blocker. Each intervention is described as alignment, governance, or strategic oversight, yet its practical function is to stop work that did not originate from the recognised authority.

Over time, capable engineers learn that producing evidence creates more friction than producing slides. Some disengage. Others leave. The organization retains the appearance of governance while losing the people most able to improve the governed system.

### The Leadership Chain That Owns No Result

The absence of accountability is rarely confined to one person. It can extend through an entire chain of leadership. Each level asks for updates, attends steering meetings, requests another plan, and passes decisions upward or downward. Everyone participates, but nobody owns the outcome.

This creates a system in which activity is visible and responsibility is diffuse. Leaders can point to the meetings they attended, the questions they asked, and the documents they requested. If the work produces no change, responsibility falls between roles: one group set the strategy, another approved the architecture, another managed delivery, and the engineers supposedly failed to execute. The chain is full of decision-makers, yet somehow has no one accountable for the decision.

More meetings are then prescribed as the cure. A failed initiative produces a review, the review creates a working group, and the working group schedules a recurring forum. The organization responds to the absence of results by generating more of the activity that failed to produce them.

Without a named owner, a measurable outcome, and a date on which the result will be examined, this cycle can continue indefinitely. No working software needs to appear. No architecture has to survive a real workload. No leader has to say, plainly, “I made this decision, it did not work, and I am responsible for changing it.”

Accountability is the mechanism that breaks the spell. It connects authority to consequence. The person empowered to approve or block a decision must also remain answerable for what that decision produces—not only for whether the correct process was followed.

### A Room That Is Both Too Permissive and Too Strict

This is why pointing out the inconsistency rarely changes anything: the same group approved a hollow proposal and blocked a sound one within the same quarter.

From inside the room, there was no inconsistency. The group applied one standard twice and acted in good faith both times. The inconsistency becomes visible only when someone can see what the standard was measuring: not whether an idea would work, but whether it sounded familiar.

### Replace Confidence with Verification

Art authentication improved by adding methods that connoisseurship could not supply on its own: pigment analysis, canvas dating, and provenance that others could inspect independently. Expertise still mattered, but it no longer had to carry the entire burden of proof.

Technical organizations need the same shift. A more senior sign-off or a larger review meeting still depends on judgment in the room. Better verification creates evidence that survives outside it.

In practice, that evidence is often unglamorous:

- a load test with agreed thresholds;
- a prototype connected to the real system;
- a threat model tied to concrete attack paths;
- an architecture decision record with acceptance criteria written before proposals are judged;
- an incremental release whose outcomes can be observed and reversed;
- a named decision owner, a measurable result, and a review date.

These tools do not remove judgment. They discipline it. They make disagreement specific, expose trade-offs, give reality a vote, and prevent accountability from dissolving into the room.

None of this requires declaring anyone incompetent. It requires recognizing that seniority, confidence, and correctness are different things. When a decision exceeds the room’s depth, the answer is not greater certainty. It is stronger evidence.

Until the room learns to demand that evidence, the forger’s spell remains intact.
