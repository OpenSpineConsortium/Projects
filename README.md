# OpenSpineConsortium · Projects (private)

Student project proposals and work, one folder per project. This repository is private:
proposals are reviewed as pull requests here, visible only to collaborators, so an idea
stays yours until it is published. Everything reusable (tools, templates, the demo study,
the ideas list, onboarding) lives in the public
[Student_Projects](https://github.com/OpenSpineConsortium/Student_Projects) repository,
and this one is cloned inside it as its `projects/` folder:

```
Student_Projects/                 public: tools, templates, examples, IDEAS.md, CLAUDE.md
└── projects/                     this repository, private
    ├── README.md
    ├── schwing_pelvic_width_dimorphism/   the worked example
    └── <lastname>_<topic>/       yours
```

`/onboard` in Claude Code clones it into place once you have been added as a collaborator
(email your GitHub username to gregory.schwing@med.wayne.edu, subject "Projects access").

## A project folder

```
<lastname>_<topic>/
├── proposal.md      the approved proposal (the pull request that started the project)
├── CLAUDE.md        copied from ../templates/ and edited for this project
├── JOURNAL.md       dated notes: what was tried, what worked, what did not
├── *.py             the scripts, one per output, run from the Student_Projects root
├── results/         per-record CSVs and reports written by the scripts
├── figures/         figures written by the scripts
└── WRITEUP.md       the abstract-length summary, then the draft
```

Proposals arrive as pull requests that add `proposal.md` only (`/new-project` writes it
with you and opens the PR). Everything else arrives in later pull requests, each naming the
ClickUp task it closes. Branch names: `proposal/<lastname>-<topic>` for the proposal,
`<lastname>/<what>` for later work. Never commit imaging data.
