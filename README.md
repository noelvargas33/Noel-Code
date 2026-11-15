# Noel Code

A personalized edition of [Suno Super Prompt](https://github.com/jasonmello/suno-super-prompt) by Jason Mello, prepared for Noel Vargas.

Create structured Suno prompts with TITLE, LYRICS, STYLE, and EXCLUDE fields. Includes arrangement and vocal guidance, genre references, complete examples, and a Python character-count and layout validator.

## Contents

- `skills/noel-code/SKILL.md`: main workflow and instructions.
- `skills/noel-code/references/`: songwriting, arrangement, duet, and troubleshooting guides.
- `skills/noel-code/examples/`: six example prompts.
- `skills/noel-code/scripts/check_prompt.py`: prompt validator (Python 3, standard library only).
- `skills/noel-code/agents/openai.yaml`: skill display information.

## Use

Load `skills/noel-code/SKILL.md` and its supporting files into an assistant that supports skills or custom instructions. Ask: "Use Noel Code to create a modern romantic salsa prompt with montuno, mambo, and coros."

Validate a prompt from the repository root:

```bash
python3 skills/noel-code/scripts/check_prompt.py my-prompt.txt
```

The combined STYLE + EXCLUDE budget is a conservative house rule, not a verified universal Suno limit. Model responses to arrangement directions vary.

## Upload to GitHub

Extract this archive and upload the contents of the `noel-code` folder to your repository, preserving the folder structure. Upload the extracted files rather than the archive if you want GitHub to show and browse the source.

## Attribution and changes

Original project: Jason Mello's Suno Super Prompt, MIT licensed. Original copyright and license are preserved in `LICENSE`.

This edition changes the skill name and display name to Noel Code, updates the invocation example, and omits the conflicting audio-processing addendum from the upstream copy. It contains no audio-watermark or AI-identifier removal tool. Core prompting references, examples, and validator derive from the original project.

This is an independent adaptation, not an official Suno product.
