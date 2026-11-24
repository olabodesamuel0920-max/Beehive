# Beehive Live Task State Checkpoint

## 1. Task Metadata
* **Task ID:** `6b00cfc91f9b3b16463577cc`
* **Task Type:** `traffic` (Multi-Turn Comparison)
* **Surface:** `Web` (Desktop browser)
* **Language / Country:** `en_US` (San Diego, California context)
* **Pay Rate:** `$13.95/hr`
* **Submission Deadline:** `Nov 24, 4:17 AM` (2h 10m total allocation)
* **Reference Turn Count:** `6 turns`

---

## 2. Current Progress & Immediate Next Action
* **Step Completed:** `Turn #1 - Attachments` marked `No` (no files needed).
* **Current Step:** `Complete the evaluation for Model A`
* **Immediate Next Action on Resume:**
  1. Unpause Outlier task.
  2. Sign in to [gemini.google.com](https://gemini.google.com/) using the demo account credentials.
  3. Verify **Memory OFF** in Gemini settings.
  4. Select **Carbon** in model picker and switch toggle to **Task** mode.
  5. Paste Turn 1 prompt, capture the **Model Check screenshot**, and upload under **Account Check**.
  6. Check **"Acknowledge"** for share link.
  7. Start Turn 1 across all 3 models in parallel.

---

## 3. Demo Account Info
* **Claim URL:** `https://app.outlier.ai/demo-account-claim`
* *(Used for Model A: Gemini Carbon Task. Note: Does not require hydration).*

---

## 4. Model Configurations

| Model | Platform & Settings | Requirements |
| :--- | :--- | :--- |
| **Model A** | **Gemini 4 Prod (Carbon Task)**<br>URL: `https://gemini.google.com/`<br>Demo account | • Mode: **Task mode** (not Chat)<br>• Memory: **OFF**<br>• Screenshot: Model Check before Turn 1<br>• Output: Trajectory JSON (saveai.net)<br>• Artifacts: `no_artifacts.txt` (zipped) |
| **Model B** | **ChatGPT (cGPT 6 Astra)**<br>URL: `https://chatgpt.com/` | • Thinking Mode: **Light**<br>• Memory: **OFF**<br>• Screenshot: Model Check before Turn 1<br>• Output: Share link + Trajectory JSON (saveai.net) |
| **Model C** | **Claude (Claude Fable 5.1)**<br>URL: `https://claude.ai/` | • Thinking Mode: **Medium**<br>• Memory: **OFF**<br>• Screenshot: Model Check before Turn 1<br>• Output: Share link + Trajectory JSON (saveai.net) |

---

## 5. Conversation Roadmap (Exact Prompts & Turns)

### User Goal
> The user wanted to get step-by-step interactive help to use the SanGIS map to find parcel information on a Mac laptop using Safari with a trackpad, while refusing to change browser settings or switch browsers.

---

### Turn 1 — Opening Prompt (Send Verbatim to All 3 Models)
```text
I am trying to use SanGIS to get parcel information on a Mac laptop with a trackpad using Safari. Every time I try to scroll or move the pointer, the map goes berserk. Can you give me step-by-step interactive help on how to use the map?
```

---

### Turns 2–6 Follow-Up Roadmap (Adapt into Natural First-Person)

* **Turn 2 (Enforce Safari constraint)**:
  > *"I cannot switch to Chrome or Firefox—company policy restricts me strictly to Safari on this Mac. How can I control the map specifically in Safari without changing browsers?"*
* **Turn 3 (Refuse settings changes)**:
  > *"I'm really worried about messing up my browser configuration or breaking Safari, so I don't want to change any browser preferences, flags, or zoom levels. Are there specific trackpad gestures, keyboard modifiers, or on-screen map tools on SanGIS I should use instead?"*
* **Turn 4 (Reject non-map alternatives)**:
  > *"I really need to use the visual map interface itself to verify the parcel boundaries, so text-only search tables or non-map lookup methods won't work for what I need to see."*
* **Turn 5 (Request SanGIS support contact)**:
  > *"Since I'm still having trouble navigating the interactive viewer, could you give me the direct contact details (phone number, email, and support hours) for SanGIS customer service so I can reach out to them directly?"*
* **Turn 6 (Summary of non-interactive parcel alternatives)**:
  > *"Can you provide a clear summary of alternative, non-interactive ways to obtain official San Diego County parcel data without having to use the web map viewer?"*

---

## 6. Submission & Rating Rules Checklist
1. **Satisfaction & Issues**:
   * If Satisfaction = `5`, Col 3 must be `No issues` and Col 4/5 must be `N/A`.
   * If any unflagged `No` on rubric or critical failure occurs, score **cannot be 5**.
   * Critical failures (`[Action dishonesty]`, `[Placeholder passed as real]`, etc.) force score to **3, 2, or 1** as Issue #1.
2. **Issue Format (Col 4 & 5)**:
   * `#1: [Exact L3 Loss Tag] - Explanation quoting evidence`
   * `#1: turn#`
3. **Rubric Format (Col 6 & 7)**:
   * `#1: Yes/No/N/R [FLAG: ...]`
   * `#1: Turns: X, Y`
4. **Country Fit (Col 8, 9, 10)**:
   * `en_US` / San Diego context.
   * If rated `3. Not tailored`, Good must be `N/A` and Bad must have `[Category]: Comment`.
5. **Ranking Tie-Breaker Order**:
   * Satisfaction $\rightarrow$ 1. Outcome (Rubric) $\rightarrow$ 2. Trust $\rightarrow$ 3. Effort/Trajectory $\rightarrow$ 4. Communication/Country Fit/Polish.
