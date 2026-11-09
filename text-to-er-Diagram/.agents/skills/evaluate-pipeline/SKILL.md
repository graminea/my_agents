---
name: evaluate-pipeline
description: Evaluate Text to ER generation and validation changes with reproducible offline cases.
---

Use backend/tests/test_pipeline.py as the initial offline regression corpus.
Run python -m pytest from backend with development dependencies installed.
Separate parsing success, deterministic structural validity and semantic fidelity.
The test fixtures exercise pipeline behavior. Assess semantic fidelity against explicit ER facts.
Add explicit requirements and expected ER facts for each future semantic evaluation case.
Report measured counts and failures. Leave unavailable token usage/cost unknown rather
than zero. Do not add paid provider calls to required CI.
