---
title: Week 12
author: Rohit Pandey
author_url: https://github.com/rohitpandey49
---

# GSoC Week 12

## Updates

- Currently working on issue [#2214](https://github.com/fossology/fossology/issues/2214) - Detecting licenses declared in LICENSE file and LICENSES folder.
- Created a new class for detecting LICENSES folder.
- Few doubts were cleared regarding the above issue.
- Suggestions by mentors on solution-
    - Use `declared licenses` in REUSE standard report.
    - REUSE standard report should be same for the whole upload.
    - Move the class for detecting LICENSES folder under `lib/php/BusinessRules` and create a new class for comparing the data/conclusion.
    - Learned to use `PHP Unit and Functional Tests` from the CLI.