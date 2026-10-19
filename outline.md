# Trustworthy data agents with commons

HMRC · October 20, 2026

Restructured for HMRC. Changes applied to `index.qmd`; placeholders marked
`[PLACEHOLDER: ...]` need real content.

## Hook: the CEO vibe-analysis problem (moved up from mid-deck)

* "What if the user is not a data scientist?" (moved from before commons).
* The Test Set / rogue analysis screenshot (moved).
* [PLACEHOLDER] CEO vibe-analysis example: someone fires up an agent,
  vibe-analyzes, gets plausible-looking analysis slop.
* Frame: this is the new normal, so the question is how to make it work.

## Pivot: models are pretty good

* The story of an eval, condensed:
    * Bluffbench counterintuitive-plot example (the diamonds slide).
    * November 2025 → September 2026: models got much better.
    * Rising tide lifts all boats; don't make statements like "LLMs can't do x"
      because it changes.
* Brief qualification (keep short, not a second warning story):
    * Bluffbench2: improvement isn't uniform (data-artifact example).
    * "Models still have deficits in skills central to data analysis."

## But they still lack context

* "Data analysis depends on context that is not in the data." Definitions,
  conventions, documentation, tacit organizational knowledge.
* A model and a harness alone are not enough.

## Two problems

1. The model has to write the right code.
2. The user has to know how trustworthy the code is.

Both problems lead directly into commons: trusted code and embedded context
help the agent produce the right analysis; showing the basis of an answer
helps the user judge how trustworthy it is.

## Commons: making this concrete

* What commons is; answer-tag examples.
* Revisit the two problems after the videos: trusted calculations and
  organizational context help with the right code; execution-based tags and
  checked context citations help the user judge trustworthiness.
* "The answers look the same" (from the SciPy talk): confident presentation
  does not distinguish wrong answers from right ones.
* Trust flow: tags reflect the recorded execution path, not a model-assigned
  confidence score.
* Trusted code: reuse calculations that data scientists already vet and
  maintain, supported by organizational context.
* Demos: devrel agent; clinical-trials agent (existing demo slides + recording);
  AML Agent (title-only demo slide).
* Build / Deploy / Improve lifecycle:
    * Build: trusted calculations, data, and context (skill, cake photo,
      three progressive layer diagrams, agent and warehouse code examples).
      Layer details not shown in the diagrams are retained in speaker notes.
    * Deploy: collaborators use the agent.
    * Improve: trajectory reviewer; review recurring questions and update
      trusted calculations and context.
* Which tool is which: commons, shinychat, querychat, Posit Assistant.

## Closing synthesis

* Code as the foundation: reproducible, transparent, auditable. A general
  philosophy illustrated by commons, not a separate solution to problem 1.
* Weave trustworthiness into the system.

## Cut from the J&J version

* Posit Assistant section: `#posit-assistant`, "Build the environment so
  that it's easy to be right", pit of success, "Performance improves when the
  environment makes it easy to be right" plot, "Design the harness with
  correctness in mind".
* Individual-oversight section: `#individual-oversight`, auto mode commands
  and Simpsons gif and evidence slide, "When should code be shown?",
  "Pause when needed".

## Still in the deck, cut candidates if time is short

* Jaggedness plot and capability profiles.
* "A rising tide lifts some of the boats" variant.
* The "How do we make data analysis agents trustworthy?" divider (kept as the
  transition into the two problems).

## Optional material

* Databot warning image as a brief opening reference.
