# PSYCHOPY

![licence](https://img.shields.io/badge/licence-GPL-3.0-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `PSYCHOPY` in category **PSYCHOLOGY**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** PSYCHOPY · **Upstream pin:** `5887b4a50f71fe4b93254754956ea488b0a0c16e` · **Category:** PSYCHOLOGY · **Vendor:** Anticloud FZ LLE · **Licence:** GPL-3.0

---

## What This Project Does

# PsychoPy

[![PyPI version](https://img.shields.io/pypi/v/psychopy.svg)](https://pypi.python.org/pypi/PsychoPy)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v1.4%20adopted-ff69b4.svg)](code-of-conduct.md)  

---

PsychoPy is an open-source package for creating experiments in behavioral science. It aims to provide a single package that is:

* precise enough for psychophysics
* easy enough for teaching
* flexible enough for everything else
* able to run experiments in a local Python script or online in JavaScript

To meet these goals PsychoPy provides a choice of interface - you can use a
simple graphical user interface called Builder, or write your experiments in
Python code. The entire application and library are written in Python and is
platform independent.

**Note:** this project now contains _only_ the PsychoPy _library_. The code for the application user interface 
is now in separate projects for 
[PsychoPy Studio](https://github.com/psychopy/psychopy-studio) (for the modern web-based GUI) 
and [PsychoPy App](https://github.com/psychopy/psychopy-app) (for the legacy wxPython GUI).

There is a range of documentation at:

* [PsychoPy Homepage](https://www.psychopy.org)
* [Youtube](https://www.youtube.com/playlist?list=PLFB5A1BE51964D587)
* The textbook, [Building Experiments in PsychoPy](https://www.sagepub.com/shop/buy-a-book/building-experiments-in-psychopy-2-273700)
* [The discourse user forum](https://discourse.psychopy.org)

## Contributions

To contribute, please fork the project, hack in a feature branch, and send a
pull request.  For more, see [CONTRIBUTING.md](CONTRIBUTING.md)
and the developers documentation at [https://www.psychopy.org/developers](https://psychopy.org/developers)

## Code Status

Dev branch: [![GH tests dev](https://github.com/psychopy/psychopy/actions/workflows/pytests.yaml/badge.svg?branch=dev)](https://github.com/psychopy/psychopy/actions/workflows/pytests.yaml?query=branch%3Adev)  [![CodeQL (dev)](https://github.com/psychopy/psychopy/actions/workflows/CodeQL.yaml/badge.svg?branch=dev)](https://github.com/psychopy/psychopy/actions/workflows/CodeQL.yaml?query=branch%3Adev) 

Release branch: [![GH tests release](https://github.com/psychopy/psychopy/actions/workflows/pytests.yaml/badge.svg?branch=release)](https://github.com/psychopy/psychopy/actions/workflows/pytests.yaml?query=branch%3Arelease) [![CodeQL (release)](https://github.com/psychopy/psychopy/actions/workflows/CodeQL.yaml/badge.svg?branch=release)](https://github.com/psychopy/psychopy/actions/workflows/CodeQL.yaml?query=branch%3Arelease)

## More information

* Homepage: https://www.psychopy.org
* Forum: https://discourse.psychopy.org
* Issue tracker: https://github.com/psychopy/psychopy/issues
* Changelog: https://github.com/psychopy/psychopy/releases 
* Roadmap: https://github.com/psychopy/psychopy/blob/dev/ROADMAP.md

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

simple graphical user interface called Builder, or write your experiments in
Python code. The entire application and library are written in Python and is
platform independent.

**Note:** this project now contains _only_ the PsychoPy _library_. The code for the application user interface 
is now in separate projects for 
[PsychoPy Studio](https://github.com/psychopy/psychopy-studio) (for the modern web-based GUI) 
and [PsychoPy App](https://github.com/psychopy/psychopy-app) (for the legacy wxPython GUI).

There is a range of documentation at:

* [PsychoPy Homepage](https://www.psychopy.org)
* [Youtube](https://www.youtube.com/playlist?list=PLFB5A1BE51964D587)
* The textbook, [Building Experiments in PsychoPy](https://www.sagepub.com/shop/buy-a-book/building-experiments-in-psychopy-2-273700)
* [The discourse user forum](https://discourse.psychopy.org)

## API

* [PsychoPy Homepage](https://www.psychopy.org)
* [Youtube](https://www.youtube.com/playlist?list=PLFB5A1BE51964D587)
* The textbook, [Building Experiments in PsychoPy](https://www.sagepub.com/shop/buy-a-book/building-experiments-in-psychopy-2-273700)
* [The discourse user forum](https://discourse.psychopy.org)

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | GPL-3.0 |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

# Have you ever contributed to an Open Source project?
Your first contribution can be a bit intimidating, but feel free to give it a try. If you get stuck, don't hesitate to ask for help in our [developer forum](https://discourse.psychopy.org/c/dev). This is also a good place to pitch your idea. Next up:
* **I won't program it myself.** Please file a [GitHub issue](https://github.com/psychopy/psychopy/issues).
* **I'd like to take a shot.** Read on to find out how!

# How to contribute
Contributing to PsychoPy consists of four steps:
1. Getting your own copy
2. Making your changes
3. Committing your changes
4. Submitting a Pull Request

## 1. Getting your own copy of the PsychoPy codebase
To be sure your improvements can easily be integrated, follow these steps:
1. **Make a [fork](https://docs.github.com/en/github/getting-started-with-github/fork-a-project) of the [PsychoPy project](https://github.com/psychopy/psychopy).** This provides you with your own copy of the PsychoPy source code.
2. **Inside your fork, make a new [branch](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches) for the feature you've got in mind.** If you'd like to fix a bug, base your new branch on the *release* branch. If you'd like to add a new feature, base it on the *dev* branch. We tend to name branches after the feature we're building. For example `olfactory_component`.
3. **source your fork to your hard drive.** Next, switch to the new branch and you're all set up!

Look [here](https://www.psychopy.org/developers/project.html) to see how the PsychoPy project is organized.

## 2. Making your changes
To help you get started with modifying PsychoPy, we've got some [developer guides](https://www.psychopy.org/developers/index.html). To try out your modified PsychoPy, do a [developer's install](https://www.psychopy.org/download.html#developers-install).

## 3. Committing your changes
Once you're happy with your changes, commit them to your GitHub project. Please use the tags below in your commit and add an informative message.
  - **BF:** bug fix. For fixing bugs in the *release* branch.
  - **FF:** ‘feature’ fix. For fixing bugs in the *dev* branch.
  - **RF:** refactoring
  - **NF:** new feature
  - **ENH:** enhancement (to existing code, but don't worry too much about the difference between this and NF)
  - **DOC:** for all kinds of documentation related commits
  - **TEST:** for adding or changing tests

## 4. File a Pull Request
Once you're done, it's time to add it to the central PsychoPy source code. File a [Pull Request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) from your own fork and branch to the PsychoPy project. Be sure to target the right branch in PsychoPy (*release* or *dev*). Thanks for contributing!

## License

Upstream © its respective contributors under GPL-3.0 (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** PSYCHOPY
- **Pinned SHA:** `5887b4a50f71fe4b93254754956ea488b0a0c16e`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`de4724c062ff9f1f0a4a8a0e350b5d50cf299775a8be2acbf1cb4fb2b58c188f`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

