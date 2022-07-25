---
title: Week 1
author: Rohit Pandey
author_url: https://github.com/rohitpandey49
---

# GSoC Week 1

This the first week of my GSoC and I am very excited to do the project and with lots of energy, hope it lasts till the end of the project.

As my first part of the project I have started working on implementing REUSE standard on Fososlogy codebase. 

REUSE was started by the Free Software Foundation Europe (FSFE) to provide a set of recommendations to make licensing your Free Software projects easier. Not only do these recommendations make it easier for you to declare the licenses under which your works are released, but they also make it easier for a computer to understand how your project is licensed.

This specification defines a standardized method for declaring copyright and licensing for software projects. The goal of the specification is to have unambiguous, human- and machine-readable copyright and licensing information for each individual file in a project. Ideally this information is embedded into every file, so that the information is preserved when the file is copied and reused by third parties.

For example, REUSE specification expects

- All text files to include SPDX copyright & licences identifiers.
- Binary files to be accompanied by a `.license` file.
- All licence texts to be available under a folder LICENSES.

## Updates

- Implemented REUSE standard in 157 files.
- Used `reuse-tool` to check status. It is a simple python tool that validates that the project is REUSE compliant, and points the files for which some information is missing if not; available at https://github.com/fsfe/reuse-tool.
- After first pull request REUSE standard status are as follows:
    ```
    - Files with copyright information: 2619 / 4360
    - Files with license information: 660 / 4360
    ```
- Raised my first pull request [#2235](https://github.com/fossology/fossology/pull/2235) - `feat(reuse): REUSE best practices for licensing/copyright` in GSoC’22 coding period to branch `contrib/reuse/change-repo-standard`.
- I proposed that a DEP5 file can be used for licensing and copyrighting of testdata files.
    - The DEP5 file MUST be named dep5 and stored in the .reuse/ directory in the root of the Project (i.e. .reuse/dep5).
    - The License tag MUST be followed by a valid SPDX License Expression describing the licensing of the associated files.
    - The Copyright tag MUST be followed by a copyright notice.