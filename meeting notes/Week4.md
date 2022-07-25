---
title: Week 4
author: Rohit Pandey
author_url: https://github.com/rohitpandey49
---

# GSoC Week 4

## Updates

- As planned in previous meetings, In the fourth week I started exploring second part of my project.

- In issue [#1513](https://github.com/fossology/fossology/issues/1513)- `Support the SPDX-FileCopyrightText keyword explicitly in the copyright agent`, I discussed the approach to identity the SPDX-FileCopyrightText keyword with mentors. Mentors suggested that a new regex should be developed to identify SPDX-FileCopyrightText correctly.

- In PR [#2040](https://github.com/fossology/fossology/pull/2040) - `feat(reso): new agent for REUSE.Software standard`, a part of the RESUSE.Software specification implemented by detecting the .license suffixed files, and applying the license detected by the Ojo agent to the associated file. Now copyright information of .license file should be copied to the associated file by Reso agent.

- To make SPDX-FileCopyrightText keyword testing easier, mentors taught the CLI method.

- In REUSE copyright and licensing standard Implementation, Raised 3rd PR [#2238](https://github.com/fossology/fossology/pull/2238) - `feat(reuse): REUSE best practices for licensing/copyright part-3`.

- Current REUSE status
    ```
    When running reuse lint, the result is as follows:

    - Files with copyright information: 4152 / 4360
    - Files with license information: 3723 / 4360
    ```

- During the implementation of the REUSE standard, I added the license and copyright information to testdata files through dep5. However, reuse tool still shows missing/bad licensing information from testdata files. Mentors suggested to raise a issue in reuse github repository. I have added an [issue](https://github.com/fsfe/reuse-tool/issues/556) to fsfe/reuse-tool for the solution to this.

- Few doubts were cleared regarding the comment formatting of the files.

- Learned about regular expressions.

## Further Plans​

- I will implement REUSE copyright and licensing information on more files
- We will discuss a solution to the issue of testdata file at our next project meeting.
- I will work on the SPDX-FileCopyrightText keyword in the copyright agent this week