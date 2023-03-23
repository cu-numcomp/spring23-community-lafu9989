# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: *Phonemizer*

Phonemizer is a python library that allows users to break words/sentences into phonemes (which are considered the smallest unit of language, usually a single sound that differentiates one word from another). Based on the [JOSS Paper](https://joss.theoj.org/papers/10.21105/joss.03958) for this project, it appears that the software has been used as a preprocessing step in a couple of text-to-speech projects (the phonemes generated can then be spoken), as well as in a few other projects. This software's audience is primarily researchers in the fields of natural language processing or linguistics. 

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL | https://github.com/bootphon/phonemizer  |
| Main/documentation website | https://bootphon.github.io/phonemizer/index.html   |
| Year project was started | 2015  |
| Number of contributors in the past year | 3 |
| Number of contributors in the lifetime of the project | 10 |
| Number of distinct affiliations | 634 (users?) |
| Where do development discussions take place? | GitHub issues |
| Typical number of emails/comments per week? | It depends, on average about 1-2 times per month a new pull request/issue is opened  |
| Typical number of commits per week? | about 1 per week when active, but hasn't been updated since July of last year |
| Typical commit size | not very big, about 1 file and 10-12 lines of code per commit for the latest ones (seems project is mostly finished) |
| How does the project accept contributions? | pull requests |
| Does the project have an automated test suite? | yes |
| Does the project use continuous integration? | yes |
| Are any legal/licensing steps required to contribute? | no |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [-] I have installed the software
- [-] I have run at least one example
- [-] I have run the test suite
- [ ] The test suite passes

### Notes/concerns/risks

Please comment on any anomalies or known risks to following this
project, if you were unable to answer any questions above, or
otherwise have concerns about the appropriateness of the software.  If
the project requires a contributor license agreement or other
procedural steps, please explain here.  "None at this time" is
acceptable for this question.

Only concerns would be that:

(1) the software hasn't been updated since last year, this doesn't meet the criteria listed in the README. However, after looking through it, I believe that it is still of reasonably high quality 

(2) the test suite has a single failure on my machine, might be related to the MacOS failure shown in Github (as I'm running a Mac). Package seems to work fine otherwise though and can be easily imported/run in Jupyter.  

(3) I'm not sure how relevant the software is to the class material, I'm pretty sure I could find some way to incorporate it (or one of the backend libraries it uses) but it might be tough especially since I don't have a background in NLP. 

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
