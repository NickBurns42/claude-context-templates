# Claude Context Templates

Fill-in templates for giving Claude meaningful context about you, your work, your home, and your interests. Drop them into Projects so Claude shows up already knowing the relevant background instead of starting every conversation from zero.

These accompany the article [*Personalize your AI aggressively. Follow one rule.*] [https://www.linkedin.com/pulse/personalize-your-ai-aggressively-follow-one-rule-andy-zehr-kznhc] — start there for the why and the how.

## What's here

| File | What it covers |
|------|----------------|
| `Me.md` | How you think, communicate, and work. The foundation that belongs in every project. |
| `Work.md` | Your role, skills, tools, and professional goals. |
| `Property.md` | Your home and property — useful for maintenance, projects, and planning. |
| `Hobby.md` | A repeatable template for any hobby or interest worth its own project. |

## How to use them

1. **Copy these into your own folder or repository.** Don't link this repo to your projects directly — these are blank templates, not personalized context. You want your filled-in versions, kept somewhere that's yours.
2. **Fill them in.** Each file has inline prompts (written as comments) guiding what goes in each section. Be honest and specific. Vague self-description produces vague results.
3. **Attach them to the matching Project.** `Me.md` goes in *every* project — it's the context that should shape every answer regardless of topic. The others go where they're relevant.
4. **Generate project instructions from them.** Once a project's files are attached, ask Claude to draft the project instructions based on what it now knows about you. Refine and save. (The article walks through this.)

## The one rule

Before you fill anything in: personalize aggressively, but never store anything that's *actionable against you* if it leaks. Account numbers, credentials, anything that authenticates you, or details that could be used against you stay out — regardless of how convenient they'd be. The shape of your life sharpens Claude's answers. The specifics that authenticate you are a liability sitting in a synced file. The article covers where that line sits and why.

## Keeping them current

Context files decay if you let them. Update yours when your situation changes, and prune what's gone stale — outdated context is worse than missing context, because it actively misleads.

## Notes

These are starting points, not a finished system. Gut what doesn't fit, rename sections, add your own. The structure matters less than the habit of giving Claude real context to work with.
