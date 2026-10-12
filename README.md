# Science Exhibition Diary

A Codex skill for turning teacher-selected classroom science-fair photos, videos, and original records into an evidence-based Traditional Chinese research diary draft.

## What it does

- Inventories a selected media folder and creates a traceable media index.
- Separates directly visible evidence, verified raw records, interpretation, and unknowns.
- Structures a diary draft using the fields on [黑熊老師科展日誌](https://science-exhibition-production.up.railway.app/).
- Keeps the draft local by default. Website creation is a distinct action that requires an explicit user request.
- Avoids identifying students from images or inventing measurements and dialogue.

## Install

Copy this folder into your Codex skills directory, typically:

`%USERPROFILE%\.codex\skills\science-exhibition-diary`

Then invoke it by asking Codex to analyze a specified folder of science-fair classroom photos and videos.

## Skill files

- `SKILL.md` — workflow, evidence rules, diary format, and website-write conditions.
- `agents/openai.yaml` — user-facing skill metadata.
- `VERSION` — current semantic version.
- `HISTORY.md` — release history.

## Use

Provide the folder containing the class photos/videos and, when available, student notes or data sheets. The skill produces a diary draft and media index. It does not publish the draft unless you explicitly ask it to create a diary entry on the website.

## License

No license has been added. All rights are reserved by default unless the owner chooses and adds a license.
