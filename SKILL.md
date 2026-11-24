---
name: "meeting-notes"
description: "Turns a meeting transcript into short notes with decisions and action items."
version: "0.1.0"
license: "MIT"
difficulty: "beginner"
est_time: "5 min"
agents: ["claude", "cursor"]
requires: []
declared_permissions: ["Read the transcript you paste"]
---

# Meeting Notes

## Output
A short summary, a list of decisions, and action items with owners.

## Steps
1. Paste the meeting transcript.
2. Ask the agent to use the meeting-notes skill.
3. Check the action items and owners.

## Example Prompt
Use the meeting-notes skill on this transcript and list action items with owners.
