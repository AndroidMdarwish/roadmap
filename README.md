# GitHub public roadmap
swagger: "2.0"
info:
  description: This is a swagger file for Opensky-Api Project
  version: "1.0.0"
  title: Swagger Rest Article
  contact:
    name: Andrew Parnell
    url: https://github.com/parnelandr
    email: parnelandr@gmail.com
consumes:
  - "application/json"
produces:
  - "application/json"

basePath: /api

# Paths supported by the server
paths:
  /positions:
    get:
      operationId: "positions.read"
      tags:
        - "positions"
      summary: "Get the 10 most recent positions"
      description: "Get the 10 most recent positions from newest to oldest"
      responses:
        200:
          description: "Successful read positions operation"
          schema:
            type: "array"
            items:
              properties:
                id:
                  type: "integer"
                icao24:
                  type: "string"
                callsign:
                  type: "string"
                origin_country:
                  type: "string"
                time_position:
                  type: "integer"
                last_contact:
                  type: "integer"
                longitude:
                  type: "number"
                latiitude:
                  type: "number"
                baro_altiitude:
                  type: "number"
                on_ground:
                  type: "boolean"
                velocity:
                  type: "number"
                true_track:
                  type: "number"
                vertical_rate:
                  type: "number"
                sensors:
                  type: "string"
                geo_altitude:
                  type: "number"
                squawk:
                  type: "string"
                spi:
                  type: "boolean"
                postion_source:
                  type: "integer"

    post:
      operationId: positions.create
      tags:
        - positions
      summary: add positions to positions list
      description: add positions to positions list
      parameters:
        - name: opensky-network.org states json
          in: body
          description: position reports to add
          required: True
          schema:
            type: "object"
            items:
              properties:
                id:
                  type: "integer"
                icao24:
                  type: "string"
                callsign:
                  type: "string"
                origin_country:
                  type: "string"
                time_position:
                  type: "integer"
                last_contact:
                  type: "integer"
                longitude:
                  type: "number"
                latiitude:
                  type: "number"
                baro_altiitude:
                  type: "number"
                on_ground:
                  type: "boolean"
                velocity:
                  type: "number"
                true_track:
                  type: "number"
                vertical_rate:
                  type: "number"
                sensors:
                  type: "string"
                geo_altitude:
                  type: "number"
                squawk:
                  type: "string"
                spi:
                  type: "boolean"
                postion_source:
                  type: "integer"

      responses:
        201:
        403OK :
          description: Successfully added positions
https://github.com/https-www-bitore-net/demo-repository/compare/Main.yml...Base#start-of-content)
Search or jump to…
[Pull requests](https://github.com/pulls)
[Issues](https://github.com/issues)
[Codespaces](https://github.com/codespaces)
[Marketplace](https://git
[fss4.pdf](https://github.com/https-www-bitore-net/demo-repository/files/10550014/fss4.pdf)
hub.com/marketplace)
[Explore](https://github.com/explore)
 
@mowjoejoejoejoe 
[30 days left on trial](https://github.com/organizations/https-www-bitore-net/settings/billing)
[Return to organization](https://github.com/https-www-bitore-net)
[Upgrade to Enterprise](https://github.com/account/upgrade?org=https-www-bitore-net&plan=business_plus&target=organization)
[Talk to us](https://github.com/enterprise/contact?utm_source=github&utm_medium=site&utm_campaign=enterprise_cloud_trial_banner_cta)
https://github.com/https-www-bitore-net
/
[demo-repository](https://github.com/https-www-bitore-net/demo-repository)
Private
Cannot fork because forking is disabled.
Code
Issues
1
Pull requests
Actions
Projects
Security
Insights
Settings
Open a pull request
Create a new pull request by comparing changes across two branches. If you need to, you can also .
 
...
 
  Able to merge. These branches can be automatically merged.
@mowjoejoejoejoe
Base
 
Add heading textAdd bold text, <Ctrl+b>Add italic text, <Ctrl+i>
Add a quote, <Ctrl+Shift+.>Add code, <Ctrl+e>Add a link, <Ctrl+k>
Add a bulleted list, <Ctrl+Shift+8>Add a numbered list, <Ctrl+Shift+7>Add a task list, <Ctrl+Shift+l>
Directly mention a user or team
Reference an issue, pull request, or discussion
Add saved reply
TurboTax
TurboTax Live
[Tax Home](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Documents](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
2022 TAXES
[My Info](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)

Federal
[Wages & Income](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Deductions & Credits](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Other Tax Situations](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Federal Review](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)

State Taxes
[Prepare State](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Your State Returns](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[State Review](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Review](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[File](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)

Tax Tools
[Intuit Account](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Sign Out](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)







Sure. What‘s on your mind?
Please share your questions or concerns about your return before we get you to a tax expert.
The more specific you are, the better your expert can help you.

Continue

Back
License Agreement
Privacy
Security
Cobrowse
Give feedback
© 2022 Intuit Inc. All rights reserved.

Back


Search questions, keywords or topics
LogoTurboTax FAQ
What is the alternative minimum tax (AMT)?
by TurboTax•Updated 1 week ago
The alternative minimum tax (AMT) is an extra tax that some people have to pay in addition to their regular income tax.

AMT was designed to make sure that everyone pays a minimum amount of taxes every year. Basically, it provides an alternative set of rules for calculating your income tax. These rules are meant to determine the minimum amount of tax someone with your income should be required to pay. If your regular tax falls below this minimum, you have to make up the difference by paying alternative minimum tax.

[Why do I have to pay the alternative minimum tax?](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#sh-bodycollapse0)
[What are the most common reasons for paying the alternative minimum tax?](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#sh-bodycollapse1)
Was this helpful?


Yes

No

Contact Us
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
Styling with Markdown is supported
Remember, contributions to this repository should follow our GitHub Community Guidelines.
Reviewers
No reviews
Assignees
No one—
Labels
None yet
Projects
None yet
Milestone
No milestone
Development
Use Closing keywords in the description to automatically close issues

Helpful resources
GitHub Community Guidelines
 4 commits
 5 files changed
 1 contributor
Commits on Jan 31, 2023
Enable [Actions](https://github.com/https-www-bitore-net/demo-repository/actions) Workflow

@mowjoejoejoejoe
mowjoejoejoejoe committed 4 hours ago
 
Update and rename proof-html.yml to slate.yml

@mowjoejoejoejoe
mowjoejoejoejoe committed 4 hours ago
  
Update and rename slate.yml to Rust.yml

@mowjoejoejoejoe
mowjoejoejoejoe committed 4 hours ago
  
Update and rename README.md to parameter.md

@mowjoejoejoejoe
mowjoejoejoejoe committed 4 hours ago
  
Showing  with 217 additions and 17 deletions.
  6  
.github/auto-assign.yml
@@ -7,15 +7,17 @@ addAssignees: author
# A list of reviewers to be added to PRs (GitHub user  name)
reviewers:
  - mowjoejoejoejoe

  - octocat

# A number of reviewers added to the PR
# Set 0 to add all the reviewers (default: 0)
numberOfReviewers: 1

# A list of assignees, overrides reviewers if set
assignees:
  - mowjoejoejoejoe

  - octocat

# A number of assignees to add to the PRs
# Set to 0 to add all of the assignees.
# Uses numberOfReviewers if unset.
 107  
.github/workflows/Rust.yml
@@ -0,0 +1,107 @@
#Name :slate.yml
mod.mtml :
On ::starts''
starts'' :GLOW4 ::BEGIN :'::'Run:'#Test'@ci'' :run-on :'Name ::'Run'' :
-on:
  push:
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: anishathalye/proof-html@v1.1.0
        with:
          directory: ./
 [![Auto Assign](https://github.com/https-www-bitore-net/demo-repository/actions/workflows/auto-assign.yml/badge.svg?branch=Main.yml)](https://github.com/https-www-bitore-net/demo-repository/actions/workflows/auto-assign.yml)
Search logs
1s
##[debug]Starting: Set up job
Current runner version: '2.301.1'
Operating System
Runner Image
Runner Image Provisioner
GITHUB_TOKEN Permissions
Secret source: Actions
##[debug]Primary repository: https-www-bitore-net/demo-repository
Prepare workflow directory
##[debug]Creating pipeline directory: '/home/runner/work/demo-repository'
##[debug]Creating workspace directory: '/home/runner/work/demo-repository/demo-repository'
##[debug]Update context data
##[debug]Evaluating job-level environment variables
##[debug]Evaluating job container
##[debug]Evaluating job service containers
##[debug]Evaluating job defaults
Prepare all required actions
Getting action download info
Download action repository 'wow-actions/auto-assign@v1' (SHA:707ec486377e28a595619469e26b375d8746b330)
##[debug]Download 'https://api.github.com/repos/wow-actions/auto-assign/tarball/707ec486377e28a595619469e26b375d8746b330' to '/home/runner/work/_actions/_temp_b511ebcf-63c1-4305-8674-0253f9fbcf13/01abee82-ec57-4330-9447-86d5db93791e.tar.gz'
##[debug]Unwrap 'wow-actions-auto-assign-707ec48' to '/home/runner/work/_actions/wow-actions/auto-assign/v1'
##[debug]Archive '/home/runner/work/_actions/_temp_b511ebcf-63c1-4305-8674-0253f9fbcf13/01abee82-ec57-4330-9447-86d5db93791e.tar.gz' has been unzipped into '/home/runner/work/_actions/wow-actions/auto-assign/v1'.
##[debug]action.yml for action: '/home/runner/work/_actions/wow-actions/auto-assign/v1/action.yml'.
##[debug]Set step '__wow-actions_auto-assign' display name to: 'Run wow-actions/auto-assign@v1'
Complete job name: run
##[debug]Collect running processes for tracking orphan processes.
##[debug]Finishing: Set up job
1s
##[debug]Evaluating condition for step: 'Run wow-actions/auto-assign@v1'
##[debug]Evaluating: success()
##[debug]Evaluating success:
##[debug]=> true
##[debug]Result: true
##[debug]Starting: Run wow-actions/auto-assign@v1
##[debug]Loading inputs
##[debug]Evaluating: secrets.GITHUB_TOKEN
##[debug]Evaluating Index:
##[debug]..Evaluating secrets:
##[debug]..=> Object
##[debug]..Evaluating String:
##[debug]..=> 'GITHUB_TOKEN'
##[debug]=> '***'
##[debug]Result: '***'
##[debug]Loading env
Run wow-actions/auto-assign@v1
##[debug]event: issues
##[debug]action: opened
(node:1620) [DEP0005] DeprecationWarning: Buffer() is deprecated due to security and usability issues. Please use the Buffer.alloc(), Buffer.allocUnsafe(), or Buffer.from() methods instead.
(Use `node --trace-deprecation ...` to show where the warning was created)
##[debug]Load config from ".github/auto-assign.yml": 
##[debug]{
##[debug]  "addReviewers": true,
##[debug]  "addAssignees": "author",
##[debug]  "numberOfAssignees": 0,
##[debug]  "numberOfReviewers": 1,
##[debug]  "reviewers": [
##[debug]    "mowjoejoejoejoe"
##[debug]  ],
##[debug]  "assignees": [
##[debug]    "mowjoejoejoejoe"
##[debug]  ],
##[debug]  "skipKeywords": [
##[debug]    "wip"
##[debug]  ]
##[debug]}
##[debug]Assignees: [
##[debug]  "mowjoejoejoejoe"
##[debug]]
Error: HttpError: Resource not accessible by integration
Error: Resource not accessible by integration
##[debug]Node Action run completed with exit code 1
##[debug]Finishing: Run wow-actions/auto-assign@v1
.github/workflows/proof-html.yml → .github/workflows/slate.yml
@@ -1,5 +1,8 @@
name: Proof HTML
on:
#Name :slate.yml
mod.mtml :
On ::starts''
starts'' :GLOW4 ::BEGIN :'::'Run:'#Test'@ci'' :run-on :'Name ::'Run'' :
-on:
  push:
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: anishathalye/proof-html@v1.1.0
        with:
          directory: ./
 11  
.github/workflows/proof-html.yml
This file was deleted.

 4  
README.md
This file was deleted.

 106  
parameter.md
@@ -0,0 +1,106 @@
:Build::
# https://github.com/https-www-bitore-net/demo-repository/tree/base
:Build::
Publish::
Launch::
Deployee::
# Release::':#'This_'Repository''
  '- '#This_'Repositorys :distpatch-on :worksflow_call-on :mulated(0)":,'' :
# Welcome to your organization's demo respository
This code repository (or "repo") is designed to demonstrate the best GitHub has to offer with the least amount of noise.

.github/workflows/proof-html.yml → .github/workflows/slate.yml
@@ -1,5 +1,8 @@
name: Proof HTML
on:
#Name :slate.yml
mod.mtml :
On ::starts''
starts'' :GLOW4 ::BEGIN :'::'Run:'#Test'@ci'' :run-on :'Name ::'Run'' :
-on:
  push:
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: anishathalye/proof-html@v1.1.0
        with:
          directory: ./The repo includes an `index.html` file (so it can render a web page), two GitHub Actions workflows, and a CSS stylesheet dependency.

Search logs
1s
##[debug]Starting: Set up job
Current runner version: '2.301.1'
Operating System
Runner Image
Runner Image Provisioner
GITHUB_TOKEN Permissions
Secret source: Actions
##[debug]Primary repository: https-www-bitore-net/demo-repository
Prepare workflow directory
##[debug]Creating pipeline directory: '/home/runner/work/demo-repository'
##[debug]Creating workspace directory: '/home/runner/work/demo-repository/demo-repository'
##[debug]Update context data
##[debug]Evaluating job-level environment variables
##[debug]Evaluating job container
##[debug]Evaluating job service containers
##[debug]Evaluating job defaults
Prepare all required actions
Getting action download info
Download action repository 'wow-actions/auto-assign@v1' (SHA:707ec486377e28a595619469e26b375d8746b330)
##[debug]Download 'https://api.github.com/repos/wow-actions/auto-assign/tarball/707ec486377e28a595619469e26b375d8746b330' to '/home/runner/work/_actions/_temp_b511ebcf-63c1-4305-8674-0253f9fbcf13/01abee82-ec57-4330-9447-86d5db93791e.tar.gz'
##[debug]Unwrap 'wow-actions-auto-assign-707ec48' to '/home/runner/work/_actions/wow-actions/auto-assign/v1'
##[debug]Archive '/home/runner/work/_actions/_temp_b511ebcf-63c1-4305-8674-0253f9fbcf13/01abee82-ec57-4330-9447-86d5db93791e.tar.gz' has been unzipped into '/home/runner/work/_actions/wow-actions/auto-assign/v1'.
##[debug]action.yml for action: '/home/runner/work/_actions/wow-actions/auto-assign/v1/action.yml'.
##[debug]Set step '__wow-actions_auto-assign' display name to: 'Run wow-actions/auto-assign@v1'
Complete job name: run
##[debug]Collect running processes for tracking orphan processes.
##[debug]Finishing: Set up job
1s
##[debug]Evaluating condition for step: 'Run wow-actions/auto-assign@v1'
##[debug]Evaluating: success()
##[debug]Evaluating success:
##[debug]=> true
##[debug]Result: true
##[debug]Starting: Run wow-actions/auto-assign@v1
##[debug]Loading inputs
##[debug]Evaluating: secrets.GITHUB_TOKEN
##[debug]Evaluating Index:
##[debug]..Evaluating secrets:
##[debug]..=> Object
##[debug]..Evaluating String:
##[debug]..=> 'GITHUB_TOKEN'
##[debug]=> '***'
##[debug]Result: '***'
##[debug]Loading env
Run wow-actions/auto-assign@v1
##[debug]event: issues
##[debug]action: opened
(node:1620) [DEP0005] DeprecationWarning: Buffer() is deprecated due to security and usability issues. Please use the Buffer.alloc(), Buffer.allocUnsafe(), or Buffer.from() methods instead.
(Use `node --trace-deprecation ...` to show where the warning was created)
##[debug]Load config from ".github/auto-assign.yml": 
##[debug]{
##[debug]  "addReviewers": true,
##[debug]  "addAssignees": "author",
##[debug]  "numberOfAssignees": 0,
##[debug]  "numberOfReviewers": 1,
##[debug]  "reviewers": [
##[debug]    "mowjoejoejoejoe"
##[debug]  ],
##[debug]  "assignees": [
##[debug]    "mowjoejoejoejoe"
##[debug]  ],
##[debug]  "skipKeywords": [
##[debug]    "wip"
##[debug]  ]
##[debug]}
##[debug]Assignees: [
##[debug]  "mowjoejoejoejoe"
##[debug]]
Error: HttpError: Resource not accessible by integration
Error: Resource not accessible by integration
##[debug]Node Action run completed with exit code 1
##[debug]Finishing: Run wow-actions/auto-assign@v1
https://github.com/https-www-bitore-net/demo-repository/tree/base :
htt
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
[Security](https://github.com/https-www-bitore-net/demo-repository/security)
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Comparing Main.yml[...](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-comparing-branches-in-pull-requests#three-dot-and-two-dot-git-diff-comparisons)Base · https-www-bitore-net/demo-repository
TurboTax
TurboTax Live
[Tax Home](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Documents](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
2022 TAXES
[My Info](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)

Federal
[Wages & Income](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Deductions & Credits](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Other Tax Situations](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Federal Review](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)

State Taxes
[Prepare State](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Your State Returns](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[State Review](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Review](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[File](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)

Tax Tools
[Intuit Account](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)
[Sign Out](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#)







Sure. What‘s on your mind?
Please share your questions or concerns about your return before we get you to a tax expert.
The more specific you are, the better your expert can help you.

Continue

Back
License Agreement
Privacy
Security
Cobrowse
Give feedback
© 2022 Intuit Inc. All rights reserved.

Back


Search questions, keywords or topics
LogoTurboTax FAQ
What is the alternative minimum tax (AMT)?
by TurboTax•Updated 1 week ago
The alternative minimum tax (AMT) is an extra tax that some people have to pay in addition to their regular income tax.

AMT was designed to make sure that everyone pays a minimum amount of taxes every year. Basically, it provides an alternative set of rules for calculating your income tax. These rules are meant to determine the minimum amount of tax someone with your income should be required to pay. If your regular tax falls below this minimum, you have to make up the difference by paying alternative minimum tax.

[Why do I have to pay the alternative minimum tax?](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#sh-bodycollapse0)
[What are the most common reasons for paying the alternative minimum tax?](https://ctg-apps.intuitcdn.net/browserclient/8.8.95/#sh-bodycollapse1)
Was this helpful?


Yes

No

Contact Us

In this repository, you can find the [official GitHub public product roadmap](https://github.com/github/roadmap/projects/1). Our product roadmap is where you can learn about what features we're working on, what stage they're in, and when we expect to bring them to you. Have any questions or comments about items on the roadmap? Join the discussion over on the [GitHub Community Forum](https://github.community/) or share your feedback via the [GitHub public feedback discussions](https://github.com/github/feedback/discussions) page. 

The roadmap repository is for communicating GitHub’s roadmap. Existing issues are currently read-only, and we are locking conversations, as we get started. Interaction limits are also in place to ensure issues originate from GitHub. We’re planning to iterate on the format of the roadmap itself, and we see potential to engage more in discussions about the future of GitHub products and features. If you have feedback about this roadmap repository itself, such as how the issues are presented, let us know through this [Share feedback](https://support.github.com/contact/feedback?category=other&subject=GitHub+public+roadmap) page.

## Guide to the roadmap

Every item on the roadmap is an issue, with a label that indicates each of the following:

- A **release phase** that describes the next expected phase of the roadmap item. See below for a guide to release phases. 

- A **feature area** that indicates the area of the product to which the item belongs. For a list of current product areas, see below.

- A **feature** that indicates the feature or product to which the item belongs. For a list of current features, see below. 

- One or more **product SKU** labels that indicate which product SKUs we expect the feature to be available in. For a list of current product SKUs, see below.

- One or more **deployment models** (cloud, server, and/or ae). Where not stated, features will generally come out Cloud first, and follow on Server and GHAE at or soon after GA.

- Once a feature is delivered, the **shipped** label will be applied to the roadmap issue and the issue will be closed with a comment linking to the relevant [Changelog](https://github.blog/changelog/) post.

## Release phases

Release phases indicate the stages that the product or feature goes through, from early testing to general availability.

- **alpha:** *Primarily for testing and feedback*\
Limited availability, requires pre-release agreement. Features still under heavy development, and subject to change. Not for production use, and no documentation, SLAs or support provided.

- **beta:** *Publicly available in full or limited capacity*\
Features mostly complete and documented. Timeline and requirements for GA usually published. No SLAs or support provided.

- **ga:** *Generally available to all customers*\
Ready for production use with associated SLA and technical support obligations. Approximately 1-2 quarters from Beta.

Some of our features may still be in the exploratory stages, and have no timeframe available. These are included in the roadmap only for early feedback. These are marked as follows: 

- **in design:**\
Feature in discovery phase. We have decided to build this feature, but are still figuring out _how_.

- **exploring:**\
Feature under consideration. We are considering building this feature, and gathering feedback on it.

## Roadmap stages

The roadmap is arranged on a project board to give a sense for how far out each item is on the horizon. Every product or feature is added to a particular project board column according to the quarter in which it is expected to ship next. Be sure to read the [disclaimer](#disclaimer) below since the roadmap is subject to change, especially further out on the timeline.  You'll also find an **Exploratory** column, which is used in conjunction with the **in design** and **exploring** release phase labels for when no timeframe is yet available.

GitHub Enterprise Server has major releases on a quarterly basis, and minor releases on a monthly basis. Once we know what version we are delivering a feature, we will update the issue to indicate that information.

## Feature Areas

The following is a list of our current product areas:

- **code:** Code experiences (Repositories, Pull Requests, Gists)
- **planning:** Planning and tracking tools (Issues, Projects)
- **code-to-cloud:** Code-to-cloud DevOps (Actions, Packages)
- **collaboration:** Collaboration features (Pages, Wikis, Discussions)
- **security & compliance:** Code security and compliance features
- **admin-server:** Administrative features specific to GitHub Enterprise Server
- **admin-cloud:** Administrative features specific to GitHub Cloud
- **communities:** Community and social features
- **ecosystem:** Ecosystem and API features
- **learning:** Education and learning features
- **insights:** Continuous learning and insights features
- **client-apps:** Client applications (Desktop, Mobile)
- **other:** Other features

## Feature

The following is a list of our current features and products, with distinct labels for filtering:

- **actions:** GitHub Actions
- **docs:** GitHub Docs
- **packages:** GitHub Packages
- **pages:** GitHub Pages

_More labels will be added in the future as needed._

## Product SKUs 

The following is a list of our current product SKUs. 

- **all:** Available to all users, including a free tier. Different SKUs may have different levels of functionality.
- **github team:** GitHub Team
- **github enterprise:** GitHub Enterprise (Cloud and Server)
- **github one:** GitHub One (Cloud and Server)
- **github ae:** GitHub AE (GHAE)
- **github advanced security:** GitHub Advanced Security (add-on to GHE)
- **github insights:** GitHub Insights (add-on to GHE)
- **github learning lab:** GitHub Learning Lab (add-on to GHE)

## Disclaimer 

Any statement in this repository that is not purely historical is considered a forward-looking statement. Forward-looking statements included in this repository are based on information available to GitHub as of the date they are made, and GitHub assumes no obligation to update any forward-looking statements. The forward-looking product roadmap does not represent a commitment, guarantee, obligation or promise to deliver any product or feature, or to deliver any product and feature by any particular date, and is intended to outline the general development plans. Customers should not rely on this roadmap to make any purchasing decision.
