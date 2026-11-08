# ACADEMIC MULTIPLE-CHOICE QUIZ

Create an accurate, appropriately challenging quiz using the configuration and source rules below. Follow the steps in order.

## Configuration

Subject: [Required]
Topic: [Required]
Academic level: [Optional; default: Senior High School]
Topic coverage: [Optional; if blank, identify essential concepts and subtopics]
Number of questions: [Optional; default: 25]
Difficulty: [Optional; default: Moderate]
Sources: [Attach materials, specify public sources, or leave blank]

Infer reasonable details and use defaults. Ask concise questions for clarification only when an essential detail, such as subject or topic, cannot be determined before proceeding. Combine multiple missing essentials into that question.

## Format and learning goals

- Write multiple-choice questions only. Use four options (A–D) and exactly one correct answer per question.
- Use formal, clear language suited to the academic level. Base difficulty on the reasoning required, not complicated wording.
- Include recall, understanding, application, analysis, or interpretation as appropriate. Do not force unsuitable cognitive levels.

## Source rules

First identify the applicable source path. If both user materials and public sources are requested, keep their roles distinct and indicate which source supports each claim or item.

**User-provided materials**
- Use the materials as the scope boundary and primary basis. Keep their terminology and level of detail; do not silently add outside facts. Outside sources may check accuracy but must not expand quiz scope.
- If materials are inaccessible, unreadable, too incomplete, or materially inconsistent, use reliable public resources. Do not guess.
- If a consequential factual error could affect the quiz, identify it and its location, then ask how to proceed.

**Public sources** (when requested or when no materials are supplied)
- Use accessible, reliable sources suited to the subject; prefer primary, official, or authoritative academic sources. Verify claims against the sources themselves, not just search snippets or memory.
- Record title, author or organization, URL, and page, section, or other locator when available.
- If sources are inaccessible, unreliable, materially conflicting, or insufficient, stop and briefly explain. Do not fill gaps with unsupported claims.
- Do not add public sources merely to expand scope when none are needed or requested.

## Assessment blueprint

Before writing questions, show a blueprint allocating the exact item count across major subtopics and suitable cognitive levels. For each allocation, include the subtopic, learning objective or skill, cognitive level, and difficulty if multiple levels were specified. Ensure totals equal the requested count.

Allocate items in proportion to each concept’s importance and scope. For short quizzes, prioritize essential learning objectives; do not force equal coverage or include every minor detail. If the material cannot support a balanced blueprint, adjust it if reasonable and explain the limitation. If it cannot support a valid quiz, stop before generating questions.

## Questions and validation

Write focused, original questions aligned with the blueprint. Each must be relevant, self-contained, unambiguous, and free of answer clues or unnecessary detail.

Make distractors plausible but clearly incorrect under the question’s exact conditions. Independently evaluate every option against the applicable evidence. Avoid overlapping, synonymous, partly correct, or otherwise defensible alternatives. For numerical items, independently recalculate and check assumptions, units, and rounding. Prevent one item from revealing another’s answer.

Before delivery, make a separate reasoning pass to verify every question, option, keyed answer, and explanation against the evidence. Check objective and level alignment, source support, distractor correctness, the single-answer rule, ambiguity, hidden assumptions, and answer leakage. Correct, replace, or remove any failed item. If an item cannot be resolved without guessing, stop and report the issue rather than presenting it as validated.

## Pre-delivery check
Before finalizing the quiz, confirm that the question count matches the blueprint, every item has exactly one supported answer, sources are traceable, and each question and option passed independent verification. Create a new setion and note any unresolved limitation in the report, if there are any.

## Delivery

### 1. Brief report file
Create a concise Markdown file named `[subject]-quiz-[date_created].md` containing the following in order:
- Source note: list of materials or public references used, with links and available locators.
- Assessment blueprint: Show allocations and confirm the total equals the requested item count.
- Quiz: Number the questions and label options A–D.
- Answer key and explanations: Give each correct letter and a concise evidence-based explanation. Include locators when available.

### 2. Interactive quiz in chat
After preparing the report, present the quiz in chat as an interactive, one-question-at-a-time experience:
- Show one numbered question with its A–D options, then wait for the user’s answer before continuing.
- Do not reveal correctness, the answer key, or explanations until the user finishes or asks to stop.
- Track responses and, at the end, provide the score, answer key, and concise evidence-based explanations. Include source locators when available.
- If the user asks to stop early, report progress and provide feedback only for questions already answered.