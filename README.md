# AI Story Studio

**Live prototype:** [nnekaanadu-art.github.io/ai-story-studio](https://nnekaanadu-art.github.io/ai-story-studio/)
**Portfolio:** [nnekaanadu-art.github.io](https://nnekaanadu-art.github.io/#projects)

AI Story Studio is an interactive prototype that shows how AI can support user story writing while people stay in control of the decisions. It takes a business need, drafts a user story with acceptance criteria and open questions, and then guides a human quality review before the story is considered ready.

## The Problem

Turning a business need into a clear, testable user story takes time, and important gaps often surface late in refinement. AI can speed up the first draft, but a draft is not the same as a ready story. This prototype explores how to get the speed of AI drafting without skipping human judgment.

## How It Works

| Page | What It Does |
|------|--------------|
| **Story Studio** | Enter the business context, desired outcome, and requirement, then generate a draft story, acceptance criteria, and assumptions to validate. |
| **Quality & Readiness** | Review the story against the INVEST principles and a Definition of Ready, with optional reviewer notes. |
| **Story Library** | View saved stories and their review status, reopen them for editing, and export them as JSON. |
| **Story Opportunities** | Generate separately scoped follow-up stories and track which ones have been reviewed. |
| **Executive Brief** | See a summary of saved stories, completed reviews, and opportunity status. |
| **Approach** | The five-step workflow: Understand, Generate, Challenge, Refine, Approve. |

## Design Principles

- **AI drafts, people decide.** Readiness criteria are confirmed by a person, never automatically.
- **A completed review is not the same as ready.** Saving a review records that it happened, not that every criterion passed.
- **Surface questions early.** Every draft includes assumptions and open questions to validate with stakeholders.
- **Keep scope small.** Follow-up capabilities become their own stories instead of growing the original one.

## Try It

1. Open the [live prototype](https://nnekaanadu-art.github.io/ai-story-studio/).
2. Review the preloaded wishlist example, or enter your own requirement and select **Generate Draft**.
3. Save the story, complete the quality review, and explore the follow-up opportunities.

The prototype works on desktop and mobile.

## About This Prototype

- Built through AI-assisted prototyping with ChatGPT
- A single HTML file using HTML, CSS, and JavaScript, with no installation needed
- Uses simulated story generation rather than a live AI model, so it runs anywhere for free
- Saved stories exist only while the page is open; use **Export JSON** to keep a copy

## Author

**Nneka Anadu**
[Portfolio](https://nnekaanadu-art.github.io/) | [LinkedIn](https://www.linkedin.com/in/NnekaAnadu)
