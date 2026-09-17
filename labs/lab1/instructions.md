# Instructions for creating Lab 1

This file specifies the content of `labs/lab1/index.html`. The page is
built from this file by an AI assistant: edit this file, then ask the
assistant to rebuild the page. The page must say what this file says,
but the exact wording on the page can be polished.

This file is also linked from the lab page itself, so students can see
an example of a real working prompt.

## Purpose of the lab

Lab 1 is an icebreaker. Each student uses an agentic AI to build a
small application ("Thingy") of their own choosing, then demos it in
class. The lab has three goals: students see for themselves how
powerful agentic AI has become, students learn the workflow of
directing an AI from a written Markdown prompt, and students meet
their classmates through what they build. This sets up the working
style used in every later lab: the student writes down what they
want, gives it to the AI, inspects the result, and steers.

## Page format

Use the standard lab page template (same as labs 2 through 8):

- Gold band at the top (`#cfb991`) with course line
  "ECE 60141 and ECE 63700" and the title
  "Lab 1: The Thingy Competition".
- White cards on a cream background, one card per block.
- The cards are grouped into two outlined boxes, "Overview" and
  "Procedure", each with a visible heading.
- No MathJax. This page has no math.
- Everything in the lab must work on Mac, Windows, and Linux.
- Bottom link: "Back to the laboratory index" pointing to
  `../../index.html`.

## Overview box

1. **The Idea.** The assignment is to build a Thingy: any application
   the student thinks would be fun to have. A game, a tool, a web
   app, a toy, something useful, something useless. The student does
   not write it — they direct an agentic AI (Claude recommended) to
   build it, and their job is to decide what to make, explain it
   clearly, look at what comes back, and steer. Due at the end of the
   first week of classes.

2. **The Rules.**
   - Any application topic; creativity encouraged.
   - An agentic AI does the building. Claude is recommended, but any
     agentic AI is fine.
   - At least part of the Thingy should be in Python, since Python is
     the language used all semester.
   - Any form is fine: web app, desktop app, command-line tool,
     notebook.

3. **The Competition.** Everyone wins. In class, students take turns
   demoing their Thingy. The audience applauds after each demo based
   on how much they like it. That is the whole scoring system.

4. **Grading.** Every student who builds a Thingy, shows it, and
   hands in the file in Step 5 gets 100% credit. No judging, no
   rubric. The applause is for glory only.

## Procedure box

1. **Step 1: Install a Markdown editor.** Briefly say what Markdown
   is and that it is the standard format for writing instructions to
   an AI. Link to the shared installation page at
   `../resources/markdown-editor.html`, which covers Mac, Windows,
   and Linux. (Lab 2 links to the same page.) The installation page
   offers two options: a lightweight editor (MacDown on Mac,
   ghostwriter on Windows and Linux) and VS Code, which also serves
   as the course IDE from Lab 2 on.

2. **Step 2: Write the prompt.** The student downloads
   `prompt-template.md` from this folder and fills it in with the
   specifics of their Thingy. The template opens with a Guidelines
   section — standing rules that apply to everything the AI produces —
   already filled in with rules for clear writing. The student should
   read the guidelines and may change them. This card also links to
   this file (`instructions.md`) as a real example of the workflow.
   The card also recommends that students be nice to their Claude:
   when a result misses the mark, explain what you meant rather than
   just saying it's wrong.

3. **Step 3: Build the Thingy.** Install the Claude desktop app from
   claude.ai/download (or another agentic AI); the ordinary app is
   enough, since the command-line environment comes in Lab 2. Drop
   the `.md` file into Claude and ask it to build what the file
   describes. Explain the iterative loop: the `.md` file is the
   record of the design; when the student changes their mind, they
   update the file and give it to Claude again, and they can also ask
   Claude to update the file.

4. **Step 4: Demo in class.** Short and light.

5. **Step 5: Hand in.** Exactly one Markdown file on Brightspace: the
   finished prompt file. The template ends with a Reflection section
   holding three headings — A) Was this fun? Why or why not?
   B) What did I learn? C) What would I do differently? — which the
   student fills in after the demo. The page should state plainly
   that only a single `.md` file is accepted: no zip files, no PDFs,
   no code.

## Notes

- Keep the tone light. This lab is meant to be fun and low-pressure.
- The demo plus the one hand-in file are the whole deliverable. No
  report.
