<h1 align="center">Google Summer of Code 2022 <img src="https://media2.giphy.com/media/KB8MHRUq55wjXVwWyl/source.gif" width="50"></h1>
<p align="center"><i>A full report on my Google Summer of Code 2022 work with FOSSology</i></p>
<p align="center"><i>Project: "Adopting REUSE standards in FOSSology" </i>  👨‍💻</p>

<p align="center">
  <a href="https://docs.google.com/document/d/1wqwygalrCRcDtv4bpXvVpuYW98X3FLacsAtgNEOdNdM/edit?usp=sharing"> Proposal </a>|
  <a href="meeting notes"> Meeting Notes </a>|
  <a href="https://medium.com/@rohit.pandey4900">Blogs</a> |
  <a href="#additional-info"> Links</a>
</p>

<figure>
  <img src="resources/Fossology.png" align="center">
</figure>

## Google Summer of Code 2022 🚩 Report: "Adopting REUSE standards in FOSSology" 👨‍💻

![ViewCount](https://views.whatilearened.today/views/github/rohitpandey49/GSoC22-Fossology-REUSE.svg)
![GitHub](https://img.shields.io/github/followers/rohitpandey49?style=social)
![Twitter](https://img.shields.io/twitter/follow/ipandeyrohit?style=social)
![GitHub Stars](https://img.shields.io/github/stars/rohitpandey49/GSoC22-Fossology-REUSE?style=social)

<h1 align="center">PROJECT DESCRIPTION  <img src="https://media.giphy.com/media/dxn6fRlTIShoeBr69N/giphy.gif" width="30"></h1>

Copyright and licensing is difficult, especially when reusing software from different projects that are released under various different licenses.

REUSE was started by the Free Software Foundation Europe (FSFE) to provide a set of recommendations to make licensing your Free Software projects easier. 

Not only do these recommendations make it easier for you to declare the licenses under which your works are released, but they also make it easier for a computer to understand how your project is licensed.

This specification defines a standardized method for declaring copyright and licensing for software projects.

The goal of the specification is to have unambiguous, human- and machine-readable copyright and licensing information for each individual file in a project.

Ideally this information is embedded into every file, so that the information is preserved when the file is copied and reused by third parties.

For example, REUSE specification expects

- All text files to include SPDX copyright & licences identifiers.
- Binary files to be accompanied by a `.license` file.
- All licence texts to be available under a folder LICENSES.

Reuse-tool is a simple python tool that validates that the project is REUSE compliant, and points the files for which some information is missing if not; available at https://github.com/fsfe/reuse-tool. 

Reuse tool an be installed using `pip install reuse`.

FOSSology currently uses old methods of defining licenses on source files. Following the REUSE specs, the code base of FOSSology should be updated with new licensing format.

## Project Mentors:
  * [Shaheem Azmal M MD](https://github.com/shaheemazmalmmd)
  * [Gaurav Mishra](https://github.com/GMishx)
  * [Nicolas Toussaint](https://github.com/NicolasToussaint)
  * [Vivek Kumar](https://github.com/viv9k)
  * [Kaushlendra Pratap](https://github.com/Kaushl2208)

<h1 align="center">👨🏻‍🏫 DELIVERABLES</h1>

| Tasks   | Planned | Completed     | Remarks    |
| :---:       |    :----:   |    :---:      |    :---:      |
| Make Fossology REUSE Conpliant     | Yes       | :heavy_check_mark: | REUSE Standard implemented and raised pull request to branch `contrib/reuse/change-repo-standard` |
| Support the SPDX-FileCopyrightText keyword explicitly in the copyright agent   | Yes        | :heavy_check_mark:  |  |
| Copy Copyright finding of .license file to associated file| Yes | :x: |  |
| Detect LICENSES/ directory | Yes | :x: |    |

<h1 align="center">ACTIVITY REPORTS</h1>

## Community Bonding - May 20th to June 12th, 2022
| Blog Title | Link |
| ---   | ---| 
Accepted for Google Summer of Code with Fossology|[Click here](https://medium.com/@rohit-pandey/accepted-for-gsoc22-with-fossology-eddebf25f8ee)
GSoC’22 Community Bonding period with Fossology|[Click here](https://medium.com/@rohit-pandey/gsoc22-community-bonding-period-with-fossology-babbeb7025b8)

## Coding Period 1 - June 13th to July 24th, 2022
| Week Number | Weekly Summary|
| --- | ---|
**WEEK 1** |[Coding Period 1 week 1](/meeting%20notes/Week1.md)
**WEEK 2** |[Coding Period 1 week 2](/meeting%20notes/Week2.md)
**WEEK 3** |[Coding Period 1 week 3](/meeting%20notes/Week3.md)
**WEEK 4** | [Coding Period 1 week 4](/meeting%20notes/Week4.md)
**WEEK 5** | [Coding Period 1 week 5](/meeting%20notes/Week5.md)
**WEEK 6** | [Coding Period 1 week 6](/meeting%20notes/Week6.md)

## Coding Period 2 - July 25th to September 5th, 2022
| Week Number | Weekly Summary|
| --- | ---|
**WEEK 7** |[Coding Period 2 week 7](/meeting%20notes/Week7.md)
**WEEK 8** |[Coding Period 2 week 8](/meeting%20notes/Week8.md)
**WEEK 9** |[Coding Period 2 week 9]
**WEEK 10** | [Coding Period 2 week 10]
**WEEK 11** | [Coding Period 2 week 11]
**WEEK 12** | [Coding Period 2 week 12]


# Let's get connected!
- [Connect with me on LinkedIn](https://www.linkedin.com/in/ipandeyrohit)
- [Give a follow on GitHub](https://github.com/rohitpandey49)
- [Follow me at Twitter](https://twitter.com/ipandeyrohit)
- [Read my blogs on Medium](https://medium.com/@rohit.pandey4900)

[![](https://img.shields.io/badge/Made%20With%20❤️%20By-Rohit-red)](https://github.com/rohitpandey49)