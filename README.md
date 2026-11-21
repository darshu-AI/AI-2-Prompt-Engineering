# AI-2: Prompt Engineering Experiments

**Internship:** Valentius Kryptix AI  
**Model:** Gemini 4 Hydrogen  
**Platform:** Google AI Studio

This repository documents three prompt engineering experiments:
1. Zero-shot vs. few-shot sentiment classification
2. Direct vs. stepwise prompting for a math problem
3. Structured JSON extraction tested on five inputs

## Files
- `AI-2-Final-Report.docx` — consolidated report
- `Experiment-1-Zero-shot-Few-shot.txt` — Experiment 1 prompts, outputs, comparison
- `Experiment-2-Chain-of-Thought.txt` — Experiment 2 prompts, outputs, comparison
- `Experiment-3-Structured-Output.txt` — Experiment 3 prompt and five outputs

## Results
- Experiment 1: Both prompt styles returned Neutral for the test feedback.
- Experiment 2: Both prompt styles answered ₹70; stepwise prompting showed more detail.
- Experiment 3: 5/5 outputs passed validation (100% for this small test).

## Limitations
Experiments 1 and 2 used the same Gemini chat, which may have allowed earlier context to influence later outputs. The sample size was small.

AI was used to assist with organizing, reviewing, and drafting the documentation. Prompts were run in Google AI Studio and outputs were recorded from the actual runs.
