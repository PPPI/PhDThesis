# Improving Software Project Health using Machine Learning
This is the main repository for my PhD thesis. Many of the chapters are imported directly from paper repositories that are not publically available.
For a PDF version, once the embargo lifts, please see [here](https://discovery.ucl.ac.uk/id/eprint/10116742/).

To cite, please use:
```bibtex
@phdthesis{partachi2021improvinglearning,
  author = {Partachi, P-P},
  editor = {Barr, E},
  school = {},
  title = {Improving Software Project Health Using Machine Learning},
  year = {2021},
  keyword = {project health},
  keyword = {software engineering},
  keyword = {applied machine learning},
  language = {English},
  conference = {UCL (University College London)},
  publicationstatus = {accepted},
}
```

## Abstract

In recent years, systems that would previously live on different platforms have been integrated 
under a single umbrella. The increased use of GitHub, which offers pull-requests, issue tracking 
and version history, and its integration with other solutions such as Gerrit, or Travis, as well as 
the response from competitors, created development environments that favour agile methodologies by 
increasingly automating non-coding tasks: automated build systems, automated issue triaging etc. In 
essence,  source-code hosting platforms shifted to continuous integration/continuous delivery 
(CI/CD) as a service.  This facilitated a shift in development paradigms, adherents of agile 
methodology can now adopt a CI/CD infrastructure more easily. This has also created large, publicly 
accessible sources of source-code together with related project artefacts: GHTorrent and similar 
datasets now offer programmatic access to the whole of GitHub.

Project health encompasses traceability, documentation, adherence to coding conventions, tasks that 
reduce maintenance costs and increase accountability, but may not directly impact features.  
Overfocus on health can slow velocity (new feature delivery) so the Agile Manifesto suggests 
developers should travel light — forgo tasks focused on a project health in favour of higher 
feature velocity.  Obviously, injudiciously following this suggestion can undermine a project’s 
chances for success.

Simultaneously, this shift to CI/CD has allowed the proliferation of Natural Language or Natural 
Language and Formal Language textual artefacts that are programmatically accessible: GitHub and 
their competitors allow API access to their infrastructure to enable the creation of CI/CD bots.  
This suggests that approaches from Natural Language Processing and Machine Learning are now 
feasible and indeed desirable. This thesis aims to (semi-)automate tasks for this new paradigm and 
its attendant infrastructure by bringing to the foreground the relevant NLP and ML techniques.

Under this umbrella, I focus on three synergistic tasks from this domain: (1) improving the 
issue-pull-request traceability, which can aid existing systems to automatically curate the issue 
backlog as pull-requests are merged; (2) untangling commits in a version history, which can aid the 
beforementioned traceability task as well as improve the usability of determining a fault 
introducing commit, or cherry-picking via tools such as git bisect; (3) mixed-text parsing, to 
allow
better API mining and open new avenues for project-specific code-recommendation tools.
