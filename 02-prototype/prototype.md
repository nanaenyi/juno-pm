# Prototype · Juno

> Module 2 · Prototype. The working build that tests your idea, made with your build tool of choice.

## Prototype link

_The public share URL from your build tool. No share URL? A screenshot of the working flow is fine, the prompt is what is assessed._

 https://claude.ai/artifact/SpUU3bMtauxXjCcEfDzKaG

## What it demonstrates

_The one flow this prototype proves._

The Risk Radar is an Insights screen the PM opens before standup, showing the top 3 risks with Slack and Jira sources.
It proves the PM scans 3 cited rows, trusts them, copies a draft standup note, and pastes it themselves.



## Debrief

- **What worked:** Pasting the skill file’s Constraints and Format into the build prompt. v2 came out cited, honest about ambiguity, copy-only, and on one page. The v1/v2 toggle also makes the redo easy to teach.
- **What broke / felt like a toy:** v1 invented “helpful” features (auto-assign, Slack posting, made-up ARR) because the prompt never mentioned Juno’s rules. Even v2 is a toy: the data is fake, the ranking isn’t real, and the source chips don’t link anywhere.
- **What I'd change next pass:** Make the source chips open a sample thread or ticket so trust can actually be tested. Show why each risk ranks where it does. Update the skill file to cite Slack thread links and Notion pages, and to allow a private draft DM to the PM.

