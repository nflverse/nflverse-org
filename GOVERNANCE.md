<!-- 
This governance model is adapted from:
- the ggplot2 governance model <https://github.com/tidyverse/ggplot2/blob/main/GOVERNANCE.md>
- the Benevolent dictator governance model by Ross Gardler and Gabriel Hanganu <http://oss-watch.ac.uk/resources/benevolentdictatorgovernancemodel>
- tidyverse tidyups governance notes: <https://github.com/tidyverse/tidyups/blob/main/004-governance.md>
and is licensed under CC-BY-SA-4.0
-->

# nflverse Governance

The nflverse project has a large community of __users__ and __contributors__, a team of 
__Core Team__ developers, and a __Core Lead__. This document details how the project
is governed and what the various responsibilities are for each role in the community.

TLDR: The nflverse Core Team leads the strategy, development, and maintenance of the 
project and actively welcomes contributions from the community of users and contributors.

## Users

People who use packages, resources, and data from the nflverse are the most important 
members of the community; without these users, this project would have no purpose.

Users are encouraged to participate in the life of the project and the community 
as much as possible. User contributions help ensure that the project is satisfying 
users' needs. Common user activities include (but are not limited to):

* Evangelising about the project;
* Sharing personal projects developed with nflverse;
* Asking and answering questions on community forums, i.e. the Discord; and/or
* Providing moral support (a 'thank you' goes a long way)

Users who continue to engage with the project and its community will often find 
themselves becoming more and more involved. Such users may then go on to become 
contributors, as described below.

## Contributors

Contributors are Users who directly interact with the project on GitHub and improve
the codebase through their contributions. 
Common contributor activities may include (in addition to those of a user):

* Filing new issues;
* Requesting new features;
* Improving documentation;
* Resolving existing issues; and/or
* Submitting pull requests;

Anyone can become a contributor: there is no expectation of commitment to the project, 
no required skillset, and no selection process. The only obligation is to follow the 
[code of conduct](CODE_OF_CONDUCT.md).

Packages don’t maintain an explicit list of contributors but acknowledge them in NEWS.md, 
using data from GitHub aggregated by usethis::use_tidy_thanks(). Contributors who implement 
user facing changes are also acknowledged in NEWS.md.

<!-- Specific advice for contributing to the project can be found in
[CONTRIBUTING.md](https://github.com/tidyverse/ggplot2/blob/master/CONTRIBUTING.md). -->

## Core Team

The Core Team developers of the nflverse project are:
* [Tan Ho](https://github.com/tanho63)
* [Sebastian Carl](https://github.com/mrcaseb)
* [Ben Baldwin](https://github.com/guga31bb)
* [John Edwards](https://github.com/john-b-edwards)

Core Team developers are collectively responsible for day-to-day maintenance and development 
of the project, including responding to issues and reviewing pull requests. They are 
GitHub administrators and [package authors](https://github.com/nflverse/nflverse/blob/HEAD/DESCRIPTION), 
which means that they have the ability to make changes to project code, and receive 
credit when others cite the project.

While Core Team developers can modify code directly, this capability is rarely used. 
Instead, changes are proposed as pull requests, and are only merged after they 
have been reviewed by at least one other Core Team developer. 

As a group, the Core Team developers are also responsible for:

* Setting and clearly communicating the scope and strategic objectives of the project
* Ensuring the long term viability of the project
* Deciding on organization-wide policies, procedures, and issues

Core Team developers are recruited from contributors. An invitation to join the Core 
Team can be extended to anyone who has made a major contribution, either through 
a small number of large changes, or a consistent pattern of smaller contributions. 
Any existing Core developer can recommend a contributor be invited to the Core Team 
by emailing or messaging the Core Lead. The Core Lead will the confirm the invitation 
with the other Core Team developers.

All Core Team developers are bound by the [code of conduct](CODE_OF_CONDUCT.md).

## Core Lead

[Tan Ho](https://github.com/tanho63) is the Core Lead.

The Core Lead is a single individual, voted for by the Core Team. Once someone 
has been appointed Lead, they remain in that role until they choose to retire, or 
the Core team casts a two-thirds majority vote to remove them.

The Core Lead is responsible for coordinating and facilitating communications within 
the Core Team and between the Core Team and third parties. Where required and with the 
Core Team’s consent, the Core Lead may act on behalf of the Core Team and the nflverse
project.

The Core Lead has no additional authority over other members of the Core Team: the 
role is one of coordinator and facilitator. The Lead is also expected to ensure 
that all governance processes are adhered to, and has the casting vote in the event
an action does not receive consensus among the Core Team.

The Core Lead is bound by the [code of conduct](CODE_OF_CONDUCT.md).

# Changelog
2023-07-30: v1.0
