---
title: Week 2
author: Rohit Pandey
author_url: https://github.com/rohitpandey49
---

# GSoC Week 2

## Updates

- Resolved all the comments/feedbacks added my mentors in pull request [#2235](https://github.com/fossology/fossology/pull/2235) - `feat(reuse): REUSE best practices for licensing/copyright`.

- Current REUSE status
    ```
    When running reuse lint, the result is as follows:

    - Files with copyright information: 2619 / 4360
    - Files with license information: 1066 / 4360
    ```
- In order to make code fully reuse compliant, we discussed adding copyright information to files without copyright information. We finalized the copyright statement for such files - `SPDX-FileCopyrightText: © Fossology contributors`.

- Few doubts were cleared regarding the comment formatting of the `.sql` and `VERSION` files.

- Second PR [#2238](https://github.com/fossology/fossology/pull/2238) - `feat(reuse): REUSE best practices for licensing/copyright part-2` raised with changes to 408 files.