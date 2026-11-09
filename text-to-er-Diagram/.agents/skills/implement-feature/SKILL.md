---
name: implement-feature
description: Implement Text to ER features while preserving its ER and generation contracts.
---

Read AGENTS.md and docs/architecture.md before changing a cross-layer contract.
For domain changes, start with backend/app/er/models.py and update frontend/src/types.ts
and frontend/src/diagram.ts when affected. Keep provider output parsing in
backend/app/generations/service.py.
Use injectable generators and temporary databases to exercise failure modes offline.
For a UI change, check the browser flow with the test provider and run the frontend build.
Report the behavior delivered, checks actually run and remaining limitations.
