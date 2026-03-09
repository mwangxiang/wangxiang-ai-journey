# Document Pipeline and Memory Layering

This workflow is my current foundation for handling documents, notes, and process artifacts with AI assistance.

## Goal

The point is not just to manage information.
The point is to build a system that helps people better, supports my own growth, preserves real process, and gradually turns that work into a portfolio-worthy body of output.

## High-level principles

- preserve first, perfect later
- separate extraction from judgment
- keep process artifacts
- keep unfinished work resumable
- keep public publishing deliberate

## Processing stages

### 1. Intake
A file, webpage, image, or note enters the system.
It becomes a tracked work unit.

### 2. Staging
Before anything is "final," it goes into temporary local storage.
This protects incomplete work from being lost.

Suggested staging areas:
- `raw/`
- `extracted/`
- `refined/`
- `conversations/`
- `archive-local/`

### 3. Extraction
Extract text and structure as faithfully as possible.
If needed, use HTML as an intermediate structural restoration layer, but store final knowledge in Markdown.

### 4. Quality gate
Before refining anything, inspect whether the extracted result is good enough to continue.
Core checks include:
- broken lines
- heading hierarchy
- header/footer pollution
- OCR error rate
- table breakage
- missing image descriptions

### 5. Refinement
Only after extraction passes the quality gate should the system:
- remove noise
- mark usable content
- mark maybe-usable content
- record uncertainties
- apply higher-level judgment later

### 6. Output and archive
Create the version intended for sending or presentation.
Then record status, follow-up needs, and archive state.

## Memory layering

A key insight: not everything belongs in long-term memory.

### Put in content files
- detailed material
- process artifacts
- raw/working drafts

### Put in daily notes
- indexes
- decisions
- navigation pointers

### Put in long-term memory
- durable rules
- durable preferences
- repeated lessons

## Public vs internal

Internal preservation is the default.
Public publishing is not.

Something can be:
- preserved locally
- resumable internally
- excluded from public sharing until explicitly approved and desensitized

## Why this matters

Without this separation, AI work quickly becomes:
- noisy
- hard to resume
- hard to verify
- hard to publish safely

With this structure, the workflow becomes much more sustainable.
