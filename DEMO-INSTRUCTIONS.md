# Demo Instructions - Copilot Energy GCC - Intro to Copilot

Classification: Public

This demo uses a fictional Microsoft Fake Company created for demonstration purposes. Any resemblance to real organizations, people, products, services, or data is coincidental. Do not use customer confidential information in this repository.

## How to use this document

This is the only runbook you need for the Intro to Copilot demo. Each step tells you which file to open, the exact prompt to use when Copilot is available, what result to expect, and what to say when you cannot show Copilot in GCC. You do not need a separate prompt file.

## Demo objective

Teach Copilot fundamentals using realistic energy operations artifacts: what to open, what to ask, how to review, and what not to show in GCC.

## Required files

- Word source brief: `artifacts/work-documents/intro-to-copilot-industry-brief.docx`
- Excel readiness workbook: `artifacts/work-documents/intro-to-copilot-readiness-workbook.xlsx`
- PowerPoint briefing deck: `artifacts/work-documents/intro-to-copilot-executive-briefing.pptx`

## GCC limitation

If Copilot is not available in the GCC tenant, do not click into or imply unavailable Copilot functionality. Use the included files and presenter PPTX to narrate what the Copilot-enabled commercial tenant experience would look like. Do not use web grounding, agents, researcher-style agents, YouTube, real customer data, or private tenant details.

## 60-minute run of show

| Time | Segment | What you do |
|---:|---|---|
| 0-5 | Set context | Explain fictional Contoso Energy Services scenario and GCC limitation. |
| 5-12 | Source file tour | Open the Word, Excel, and PowerPoint work documents. |
| 12-20 | Prompting pattern | Explain role, task, context, format, and review criteria. |
| 20-42 | Main demo workflow | Run or narrate the step-by-step prompts below. |
| 42-52 | Cross-app handoff | Show how output becomes a draft response, SOP, workbook insight, or slide outline. |
| 52-58 | Human review | Review accuracy, compliance, sensitivity, tone, and feature availability. |
| 58-60 | Close | Summarize adoption guidance and Q&A handoff. |

## Step-by-step demo with prompts

### Step 1: Set context

**Open this file:** `README.md and presenter PPTX`

**Prompt to use:**

```text
No prompt. Say: This is a fictional Contoso Energy Services demo. In GCC, Copilot may not be available, so I will narrate what the Copilot-enabled commercial experience would look like and avoid showing unavailable features.
```

**Expected result:** Audience understands the boundary: fictional content, no real customer data, no web grounding, no agents.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 2: Tour the work packet

**Open this file:** `artifacts/work-documents/intro-to-copilot-industry-brief.docx`

**Prompt to use:**

```text
No prompt. Point out the Scenario, Business problem, Source notes, and Presenter guidance sections.
```

**Expected result:** Learners see that Copilot is useful when grounded in work content they already have.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 3: Explain prompt anatomy

**Open this file:** `artifacts/work-documents/intro-to-copilot-industry-brief.docx`

**Prompt to use:**

```text
Summarize this readiness brief for a cross-functional energy operations audience. Give me: 1) three key themes, 2) three risks or open questions, 3) the likely owner for each follow-up, and 4) a short reminder of what a human must review before sharing.
```

**Expected result:** A structured summary that demonstrates role, task, context, format, and review criteria.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 4: Show Excel grounding concept

**Open this file:** `artifacts/work-documents/intro-to-copilot-readiness-workbook.xlsx`

**Prompt to use:**

```text
Using the Readiness Metrics worksheet, identify the three highest-risk workstreams and explain why each one needs attention. Then suggest a next-step owner and one question to ask each owner.
```

**Expected result:** A ranked operational risk summary grounded in the workbook, not the web.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 5: Cross-app handoff

**Open this file:** `artifacts/work-documents/intro-to-copilot-executive-briefing.pptx`

**Prompt to use:**

```text
Create a five-slide executive update storyline from the Word brief and Excel risks. For each slide, include title, key message, and presenter note. Keep it suitable for an energy operations leadership audience.
```

**Expected result:** Learners understand that Copilot output can become a draft for another work product.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 6: Human review

**Open this file:** `DEMO-INSTRUCTIONS.docx`

**Prompt to use:**

```text
Create a final review checklist for this Copilot output. Include accuracy, missing context, sensitivity, compliance, tone, and whether the tenant has the required feature enabled.
```

**Expected result:** A practical review checklist learners can reuse.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 7: GCC fallback close

**Open this file:** `Presenter PPTX`

**Prompt to use:**

```text
No prompt. Say: In a Copilot-enabled commercial tenant, this is where I would run the prompt in the app. In this GCC tenant, I am not showing unavailable Copilot features.
```

**Expected result:** Clear memory cue for the presenter not to show capabilities the audience does not have.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

## Final human-review checklist

Before sharing any generated output, verify:

- The output is grounded only in the provided files.
- No customer confidential data or real tenant details were introduced.
- Any assumption is marked `[VERIFY]`.
- The tone is appropriate for the audience.
- The feature shown or described is available in the tenant being used.

## Cleanup

Remove any non-public presenter files after delivery. Keep this repository public-safe.
