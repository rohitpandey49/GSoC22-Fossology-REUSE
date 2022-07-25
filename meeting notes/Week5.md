---
title: Week 5
author: Rohit Pandey
author_url: https://github.com/rohitpandey49
---

# GSoC Week 5

## Updates

- Implemented REUSE standard in more files.

- Current REUSE status
    ```
    When running reuse lint, the result is as follows:

    - Files with copyright information: 4322 / 4360
    - Files with license information: 4284 / 4360
    ```

- In the issue I raised in fsfe/reuse-tool, I received two following suggestions/solutions:
    - Put a .license file next to your testdata files. The contents of the testdata files will be ignored, and the contents of the .license file will be used instead.
    - Put REUSE-IgnoreStart and REUSE-IgnoreEnd in your testdata files. Documentation Link.

- Discussed both solutions with mentors and decided to use the second solution i.e. `REUSE-IgnoreStart` and `REUSE-IgnoreEnd` in your testdata files.

- Mentors provided guidance on how to correctly identify SPDX-FileCopyrightText.

- Few doubts cleared regarding the comment formatting of the multiple files.

- Mentors discussed about the midterm evaluations for GSoC 2022 - open on July 25, 2022 and close 4 days later on July 29, 2022. 

## Further Plans​

- I will add ignore syntax on the test data pages.
- I will work on regular expression to correctly identify SPDX-FileCopyrightText statement.