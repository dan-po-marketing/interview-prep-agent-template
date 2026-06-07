# Interview Prep Agent Template

Public-safe scaffold for an AI assistant that prepares interview briefs and post-call review artifacts.

This repo is a template only. It contains prompts, neutral HTML templates, and workflow documentation. It does not include real interviews, transcripts, calendar exports, recordings, personal profile notes, or employer-specific data.

## Workflow

1. Create a private job folder for each interview.
2. Add job description, company notes, and resume/profile context.
3. Generate a prep brief from `prompts/generate-prep.md`.
4. After the call, add a verified transcript in the private job folder.
5. Generate a review artifact from `prompts/generate-review.md`.

## Included

- `prompts/`: prompt templates for prep and review.
- `templates/`: minimal HTML shells for rendered artifacts.
- `system/`: safe workflow notes and privacy boundaries.
- `scripts/`: placeholder scripts showing where local automation can live.

## Built with Codex

Codex was used to turn a private interview-prep workflow into a sanitized public template without publishing transcripts, calendar data, or personal interview feedback.
