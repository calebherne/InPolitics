This repo is a concise wiki about Indiana politics (statewide and Hamilton County).

- Write in bullet points and short sections (avoid long paragraphs).
- Prefer links and sources for claims (use the internet; model knowledge is outdated).
- Use the existing structure and link files with correct relative paths.
- Remaining tasks are tracked in `PoliticsTodo.md`.

## Structure (must match folders)
- Offices are in `Offices/` and Profiles are in `Profiles/`.
- Each area is split into: `State/`, `County/`, `City/`, `Federal/`, and `School Districts/`.
- GOP party positions are documented as office pages (e.g., State Party Chair, County Party Chair, Precinct Committeeman).
- Update this instruction file when prompts change the repo structure but don't update if you are just adding with not structure change.

## Offices pages (role pages)
Each office page should include:
- Requirements to hold the position.
- How the position is elected/appointed.
- Roles and responsibilities (what a usual day looks like and time commitment).
- Powers and limitations (what they can and cannot do). 
  - Include powers that technically exist but are rarely or never used (e.g. President has the ability to stack the courts but has never done so).
- Term length and re-election timing.
- Current office holder with a link to the profile.
- GOP party positions should follow this same format (e.g., State Party Chair, Precinct Committeeman).

Linking pattern (examples):
- From an office page to its profile: `../../Profiles/State/Governor - Mike Braun.md`
- Between offices in the same folder: `Lieutenant Governor.md`

## Profiles pages (person pages)
Each profile should include:
- Office link back to the office page.
- Basic info, background, and notable positions with sources.
- Links to related profiles or offices when relevant.

Linking pattern (example):
- From a profile to its office: `../../Offices/State/Governor.md`