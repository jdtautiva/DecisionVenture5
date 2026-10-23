# DecisionVenture5

> **Interactive marketing investigation for exploring mediation, moderation, and causal reasoning through team decisions, evidence comparison, and guided reflection.** Developed by Julián Díaz Tautiva, PhD

---

## Overview

**DecisionVenture5** is a browser-based pedagogical activity designed for undergraduate and graduate courses in marketing, consumer behavior, business research methods, and applied data analysis. Students work in teams of three or four and take the role of investigators examining how a promotional discount might influence purchase intention and which customers appear to respond more strongly.

The activity presents a fictional case titled **“El misterio del descuento”**. A store called *Campus* introduces a discount, and its manager wants to understand the results. Across three sequential challenges, teams construct a possible explanatory mechanism, compare their predictions with hypothetical customer data, and evaluate whether the evidence supports a causal claim. The closing stage introduces the concepts of mediation and moderation and asks teams to create a new marketing example.

Each team completes its own investigation on a shared device. Students register their team, discuss the questions, confirm their responses, and receive feedback directly within the activity. Initial responses remain recorded, while subsequent reflections are saved separately. The activity emphasizes explaining decisions, distinguishing changes from starting levels, and recognizing the additional evidence needed to support a proposed causal mechanism.

---

## Learning Objectives

By completing the activity, students are able to:

- Distinguish mediation questions about mechanisms from moderation questions about conditions or customer characteristics
- Identify a marketing action, a possible mediator, and an outcome in an explanatory sequence
- Explain how a discount could influence purchase intention through perceived value
- Formulate a prediction before examining the available evidence
- Calculate differences in purchase intention between discount and no-discount conditions
- Compare changes across customer groups without confusing the initial level with the size of the change
- Recognize a descriptive pattern consistent with moderation by customer type
- Distinguish a plausible explanatory mechanism from a demonstrated causal mechanism
- Identify temporal ordering and prior common causes as relevant considerations in causal reasoning
- Recognize that randomizing a marketing action does not automatically establish the causal role of its proposed mediator
- Revise an interpretation in response to evidence and feedback while preserving the original reasoning
- Develop a new marketing example that distinguishes an action, a mechanism, an outcome, and a potential moderator
- Communicate a team’s conclusions, uncertainties, and reflections in a downloadable report

---

## Key Features

**One device per team** — each group runs an independent investigation on its own device. Teams control their responses, pace, hints, and progression without requiring an instructor to enter answers from a central computer.

**Team registration and rotating roles** — students enter a required team name and may add their course or section and member names or initials. Suggested roles include reader, critical reviewer, and recorder; a fourth participant can monitor time. Teams are encouraged to rotate roles between challenges.

**Three sequential challenges** — the activity moves from constructing an explanation to examining evidence and questioning a managerial claim. Completing and confirming a challenge unlocks the next stage. Progression depends on participation and submission, not on answering every closed question correctly.

**Mechanism-building challenge** — teams arrange the cards *Descuento*, *Valor percibido*, and *Intención de compra* into a proposed sequence and explain why the relationships make sense. Feedback presents a possible mechanism and identifies it as a hypothesis requiring evidence.

**Prediction before evidence** — teams predict whether occasional customers, habitual customers, or both groups will show the greater increase in purchase intention. They must record their prediction and justification before opening the data. The initial prediction is preserved and is not graded.

**Comparison of customer responses** — an embedded chart and table display hypothetical purchase-intention means on a scale from 1 to 7. Teams calculate the change for each customer group, identify which group changes more, and explain whether the evidence supports their initial prediction. Numerical inputs accept either a decimal comma or a decimal point.

**Causal reasoning challenge** — teams assess a manager’s claim that simultaneous increases in perceived value and purchase intention demonstrate the mechanism. They propose an objection or an improvement to the investigation, then review feedback on temporal ordering, prior common causes, and the limits of randomizing the discount alone.

**Feedback after confirmation** — the activity compares the card sequence, numerical calculations, and selected conclusion or verdict with the expected responses. Explanations and correct calculations become visible after submission. Confirmed responses remain unchanged, and teams can add separate reflections describing what they would revise.

**Progressive hints without penalties** — each challenge includes up to three hints. Teams request additional guidance as needed, and the report records how many hints were consulted. Hint use does not reduce the suggested instructor score.

**Independent, optional timer** — each team can start, pause, reset, or extend the timer for the current stage. Reaching zero does not submit answers or advance the activity automatically.

**Conceptual closing and transfer task** — after the three challenges, the activity names and distinguishes mediation and moderation. Teams then create a different marketing case and explain how their understanding changed during the investigation. Both closing responses are required to prepare the final report.

**Completion tracker and instructor assessment** — the interface displays progress through the three challenges. This is a completion indicator, not an automatic grade. The final report includes a suggested instructor rubric awarding up to three points per challenge: one for the solution and two for the argumentation, for a maximum of nine points. Open-ended explanations require instructor review.

**Local progress saving and portable backups** — the activity attempts to save progress in the current browser using `localStorage`. If browser settings prevent this, the open tab can still hold the active session. Teams can download a JSON backup using **“Guardar avance”** and restore it using **“Cargar un respaldo”**, including when moving to another device. Local-file storage behavior can vary across browsers, so the downloadable backup provides an explicit way to retain progress.

**Team report and spreadsheet export** — the final TXT report includes team identification, confirmed answers, the initial prediction, calculations, subsequent reflections, the new marketing example, learning reflections, device timestamps, hint counts, and the instructor rubric. A separate CSV export provides structured responses for review in spreadsheet software. Downloading a file does not submit it to the instructor.

**Built-in instructions and responsive interface** — **“Cómo jugar”** explains the workflow and includes instructor guidance. The layout adapts to smaller screens and includes labeled inputs, keyboard-focus indicators, and a fullscreen option where the browser supports it. A laptop per team is recommended for discussion, writing, and file handling.

---

## Technical Details

| Attribute | Detail |
| --- | --- |
| Package name | DecisionVenture5 |
| Activity title | El misterio del descuento |
| Format | Single `.html` file, fully self-contained |
| Main file | `Detectives_de_Marketing.html` |
| Dependencies | None |
| Backend required | None |
| External libraries | None |
| Main technologies | HTML, CSS, JavaScript, inline SVG |
| Activity structure | Team setup, three challenges, and a conceptual closing |
| Team arrangement | Three or four students sharing one device; independent session per team |
| Case data | Fixed, hypothetical purchase-intention means on a 1–7 scale |
| Embedded checks | Card sequence, group differences, comparison conclusion, and causal verdict |
| Assessment | Completion tracking and formative feedback; open-ended arguments assessed by the instructor |
| Suggested rubric | Up to 3 points per challenge; 9 points in total, assigned by the instructor |
| Storage | JavaScript runtime state and optional browser `localStorage` |
| Backup and restore | Downloadable JSON file, imported through the file picker |
| Report export | UTF-8 plain-text report (`.txt`) |
| Spreadsheet export | UTF-8 CSV with a byte-order mark and semicolon delimiters |
| PDF export | No dedicated PDF export in the current version |
| Shared results | Manual submission of exported files; no live synchronization or shared leaderboard |
| Browser environment | Modern browser with JavaScript and local file downloads enabled; browser QA completed in Chrome |
| Screen | Responsive layout; laptop or desktop recommended for team use |
| Language | Spanish interface and exported reports; English README |
| Estimated duration | 12–15 minutes; allow extra time for discussion and submission |
| Course context | Marketing, consumer behavior, research methods, and applied data analysis; Session 9 on mediation and moderation |
| Instructor attribution | Julián Díaz Tautiva, PhD |

---

## Suggested Citation
Díaz Tautiva, J. A. (2026). *DecisionVenture5 - The discount mystery: Mediation, moderation, and causal reasoning* [Interactive teaching activity].
